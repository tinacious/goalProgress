# Tinacious Design Animated Goal Progress jQuery plugin

This plugin allows you to create an animated progress bar using jQuery. Just fill in the required input and the plugin calculates the progress of your goal and animates the bar. You can specify text to put before and after the amount raised.

![Screenshot of the Tinacious Goal Progress plugin](https://github.com/tinacious/goalProgress/blob/master/screenshot.png)

## Usage

Reference `goalProgress.css` and either `goalProgress.min.js` or `goalProgress.js`.

Then initialize your script.

```js
$('#goal_meter').goalProgress({
	goalAmount: 150,
	currentAmount: 100,
	textBefore: '$',
	textAfter: ' raised'
});
```