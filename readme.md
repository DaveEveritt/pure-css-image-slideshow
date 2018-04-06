# Pure CSS image slideshow using CSS animation

Cycles images in a `figure` (or any) container by varying their opacity over differing periods. The image container has a set width and `overflow: hidden`, which prevents any excess image height from showing beneath.

A [CSS variable](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables) is used to set the image and container width in one go. For IE support, delete the variable in the `body` style block and replace the variables further down with a desired width (see [CSS variable browser support](https://caniuse.com/#search=variables)).

[See demo](https://daveeveritt.github.io/pure-css-image-slideshow/).

---

Adapted and simplified from [this CodePen by Elton Kamami](https://codepen.io/eltonkamami/pen/hjBrE), with [my own images](https://www.flickr.com/photos/daveeveritt/).
