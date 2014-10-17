# Tinacious Design Animated Goal Progress Bar jQuery plugin

This plugin allows you to create an animated progress bar using jQuery. Just fill in the required input and the plugin calculates the progress of your goal and animates the bar. You can specify text to put before and after the amount raised.

![Screenshot of the Tinacious Goal Progress plugin](https://github.com/tinacious/goalProgress/blob/master/screenshot.png?raw=true)

Screenshot not enough? [Click here to see the live demo](http://tinacious.github.io/goalProgress/).

## Usage

This repository can be installed using Bower:

```bash
bower install goalProgress --save
grunt bower-install
```

1. Reference `goalProgress.css` and either `goalProgress.min.js` or `goalProgress.js`.

2. Put an empty element on the page: `<div id="sample_goal"></div>`

3. Initialize your script.
    ```js
    $(document).ready(function(){
        $('#sample_goal').goalProgress({
            goalAmount: 150,
            currentAmount: 100,
            textBefore: '$',
            textAfter: ' raised'
        });
    });
    ```

That [demo link](http://christinaholly.com/sandbox/plugins/goalProgress/) again.

## License

### The MIT License (MIT)

Copyright &copy; 2014 Tinacious Design 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/tinacious/goalprogress/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
