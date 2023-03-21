 ## freeCodeCamp.org

## Learn CSS Transforms by Building a Penguin

## In this course, you'll build a penguin. You'll use CSS transforms to position and resize the parts of your penguin, create a background, and animate your work.

## Table of contents

- [Overview](#overview)
  - [Gif](#gif)
  - [Links](#links)
  - [What I learned](#what-i-learned)


## Overview
I learned a lesson on FreeCodeCamp.org about building an animated penguin in CSS. I attempted to write the code on my own. It was a very good experience for me. This project expanded my knowledge about the possibilities of CSS

## Gif
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMGNhZDk2YmNhMDM5ZTkwOTA4ODFmMDljYzBmZjFiNjkwOWVkNGY5YiZjdD1n/onpOmUA2NiHXlhmVtf/giphy.gif"/>

### Links

- Solution URL: [Click Here](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-css-transforms-by-building-a-penguin/step-104)
- Live Site URL: [Click Here](https://your-live-site-url.com)

### What I learned

```css
:root {
  --penguin-face: white;
  --penguin-picorna: orange;
  --penguin-skin: gray;
}
.face{
background-color: var(--penguin-face);
}
.arm.left {
  top: 35%;
  left: 5%;
  transform-origin: top left; 
  transform: rotate(130deg) scaleX(-1);
  animation: 3s linear infinite wave;
}
@keyframes wave {
  10% {
    transform: rotate(110deg) scaleX(-1);
  }
}
```