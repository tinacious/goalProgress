# Tinacious Design Animated Goal Progress Bar jQuery plugin

This plugin allows you to create an animated progress bar using jQuery. Just fill in the required input and the plugin calculates the progress of your goal and animates the bar. You can specify text to put before and after the amount raised.

![Screenshot of the Tinacious Goal Progress plugin](https://github.com/tinacious/goalProgress/blob/master/screenshot.png?raw=true)

Screenshot not enough? [Click here to see the live demo](http://tinacious.github.io/goalProgress/).

## Usage

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

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/tinacious/goalprogress/trend.png)](https://bitdeli.com/free "Bitdeli Badge")