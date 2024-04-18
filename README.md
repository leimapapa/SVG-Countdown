# SVG-Countdown
SVG-only countdown clock. One call starts the SVG animation

<img src="30sec.svg" title="High noon example" height="100px">

## Dependencies

* None babay!


## Usage
Use it by pointing it to your element:

```javascript
initCountdown(elt, properties));

initCountdown(document.querySelector('#myElement'),
  {
    day: 0, //adds a day's worth of seconds to the total seconds
    hour: 0, //adds an hour's worth of seconds to the total seconds
    min: 0, //adds 60 seconds to the total seconds
    sec: 0, //seconds to add to the total seconds
    color: "#fff", //color of the numbers
    showMs: false, //whether or not to show the milliseconds
    glow: false, //whether or not to add a blur shadow behind the clock
    goldOutline: false, //whether or not to add the fancy gold outline
    font: 'Roboto, sans-serif', //default font
    fontWeight: 600, //default number thickness
    id: getUUID() //uuid to be added the clockItToMe clock svg id 
  }
);
```

## CDN
https://cdn.jsdelivr.net/gh/leimapapa/SVG-Countdown/svgcountdown.min.js


## Working Example
[codepen example](https://codepen.io/leimapapa/pen/KKYGaOJ)
