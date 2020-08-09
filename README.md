# Learning AOS (Animate On Scroll) library

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Where I first heard about it: <https://css-tricks.com/aos-css-driven-scroll-animation-library>

The library itself: <https://github.com/michalsnik/aos>

My fork of the **_anchoring triggers_** example: <https://codepen.io/hchiam/pen/MWywwdm>

My fork of the example of **_custom animation triggered by scroll position_**: <https://codepen.io/hchiam/pen/MWywwdo>

My SCSS learning repo: <https://github.com/hchiam/learning-sass>

## Example

```html
<div
  data-aos="fade-left"
  data-aos-anchor="#trigger-2"
  data-aos-anchor-placement="top-center"
></div>
```

In this example:

- `data-aos` = animation effect(s) on the `div` it's on (e.g.: `fade-left` = fade in and move in left-wards).
- `data-aos-anchor` = triggered by element with the id `trigger-2`.
- `data-aos-anchor-placement="top-center"` = top of `#trigger-2` at the `center` of the window will trigger the animation.

Also:

- `data-aos="custom-animation"` = use custom CSS styles for before (`[data-aos="custom-animation"]`) and after (`[data-aos="custom-animation"].aos-animate`)
