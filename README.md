This is a barebones example showing you how you might do search-and-highlight with plain javascript and CSS using modern browser features.

Browsers themselves have a feature where they put an indicator inside the scrollbar showing you where in the document matches are found.
We can't draw on top of the scrollbar, but we can draw next to it, so we emulate this feature as closely as possible. Firefox seems to use
a scrollbar overlay which looks nicer while Chrome reserves space for its scrollbar which takes up more space. Perhaps in the future there
will be more control over the styling options.

The highlighting works in Firefox Nightly at the time I made this. Other browsers have good support already.


[CodePen demo](https://codepen.io/hssm/pen/ZYzqxwe)
