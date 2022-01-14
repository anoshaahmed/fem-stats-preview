# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshots

- [Desktop Preview](solution-screenshots/desktop-preview.png)
- [Mobile Preview](solution-screenshots/mobile-preview.png)

### Links

- Solution URL: [FrontEnd Mentor: My Solution](https://www.frontendmentor.io/solutions/stats-preview-card-using-css-flexbox-DGP7xGCLI)
- Live Site URL: [GitHub Page: Stats Preview Card](https://anoshaahmed.github.io/fem03-stats-preview/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned the mix-blend-mode property, which I used for the overlay:
```html
<div class="mainpic">
  <div class="overlay"></div>
</div>
```
```css
section .mainpic {
    min-height: 446px;
    min-width: 540px;
    background: url(images/image-header-desktop.jpg) no-repeat center right / cover;
    border-top-right-radius: 9px;
    border-bottom-right-radius: 9px;
    opacity: 0.8;
}

section .overlay {
    height: 100%;
    width: 100%;
    background: #a743d6;
    mix-blend-mode: multiply;
    border-top-right-radius: 9px;
    border-bottom-right-radius: 9px;
}
```

### Continued development

In the future, I really aim to understand image properties more.

### Useful resources

- [MDN Web Docs: mix-blend-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) - This helped me understand the mix-blend-mode property. I really liked this pattern and will use it going forward.
- [w3schools](https://www.w3schools.com/colors/colors_hsl.asp) - I like using this to convert hsl to hex codes, and also to change up a color to my liking.
- [IMAGECOLORPICKER.com](https://imagecolorpicker.com/) - This is my favorite website to pick a color from an image. I simply paste a screenshot, and pick the color I'm looking to identify.

## Author

- Website - [Anosha Ahmed](https://www.anoshaahmed.com) - My website is not up yet, but it will be soon.
- Frontend Mentor - [@anoshaahmed](https://www.frontendmentor.io/profile/anoshaahmed)
- GitHub - [@anoshaahmed](https://github.com/anoshaahmed/)
- Twitter - [@anosha1ahmed](https://www.twitter.com/anosha1ahmed)
