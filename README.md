# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![Desktop](./screenshot/screenshot-desktop.png)
![Desktop](./screenshot/screenshot-mobile.png)

### Links

- Live Site URL: [femt-single-price-grid-component](https://mpluggie7.github.io/femt-single-price-grid-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](./style.css) - For styles

### What I learned

Use the grid layout, grid template column, grid template row and grid column span in this section.

To see how you can add code snippets, see below:

```css
main {
  width: 345px;
  display: grid;
  grid-template-rows: repeat(3, 1fr);
  border-radius: 5px;
  overflow: hidden;
  box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.1);
}

@media (min-width: 768px) {
  main {
    width: fit-content;
    grid-template-rows: auto;
    grid-template-columns: repeat(2, 345px);
  }

  .title {
    grid-column: 1 / 3;
  }
}
```

### Continued development

n/a

### Useful resources

n/a

## Author

- Website - [megamaxo-app](https://www.megamaxo-app.com)
- Frontend Mentor - [@Mpluggie7](https://www.frontendmentor.io/profile/Mpluggie7)

## Acknowledgments

n/a
