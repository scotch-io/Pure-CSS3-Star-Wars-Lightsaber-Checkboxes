Pure-CSS3-Star-Wars-Lightsaber-Checkboxes
=========================================

Pure CSS3 Star Wars Lightsaber Checkboxes. This is a quick fun little project built to demonstrate the power behind CSS3, and an awesome little checkbox hack (:checked ~ div). Not "too" practical for UI/UX, but overall some cool code.

Please attribute.

### [Demo](http://scotch.io/demos/pure-css3-star-wars-lightsaber-checkboxes) - [CodePen](http://codepen.io/ncerminara/pen/KzurJ) - [More Info](http://scotch.io)

## Features
- No JavaScript
- Plain and Simple. More for fun, less for UI/UX.
- Yoda Green Color Lightsaber
- Darth Vader Red Color Lightsaber
- Obi-Wan Kenobi Blue Color Lightsaber
- Mace Windu Purple Color Lightsaber
- On and Off Switch Colors
- Optimized for Webkit. Cross-browser support. IE9+.
- Governed under MIT Open Source License. Please attribute though.
 

## How to Use

Just include the `lightsaber.css` file on the page you would like to have the lightsaber checkboxes.

```html
<link rel="stylesheet" href="/path/to/lightsabers.css">
```

Where you want a checkbox, just paste this snippet:

 
```html
<div class="lightsaber">
	<label for="yoda-example"></label>
	<input type="checkbox" id="yoda-example" checked="checked">
	<div class="switch"></div>
	<div class="plasma yoda"></div>
</div>
```


## Swapping Out Lightsaber Colors

There are 4 colors included:
- Yoda Green
- Darth Vader Red
- Obi-Wan Kenobi Blue
- Mace Windu Purple

To use different colors, where `<div class="plasma yoda"></div>`, swap out `yoda` with either:
- `vader`
- `obi-wan`
- `windu`

## License (MIT)

Copyright (c) 2013. scotch.io

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.