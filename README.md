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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](images/Desktop_view.png)

### Links

- [Solution URL](https://github.com/jleegunn/single-price-grid)
- [Live Site URL](https://jleegunn.github.io/single-price-grid/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I learned more about CSS grid and inline-grid function and how to make them responsive.

To see how you can add code snippets, see below:

```css
@media (max-width: 900px) {
  .box3 {
    grid-template-columns: repeat(1, 1fr);
    width: 330px;
  }

  .inline1, .inline2, .inline3 {
    grid-column: 1 / 1;
    padding: 10px 25px 20px;
  }
}
```

### Useful resources

- [Example resource 1](https://travishorn.com/responsive-grid-in-2-minutes-with-css-grid-layout-4842a41420fe) - This helped me t understand how to take the grid and make it responsive.


## Author

- Website - [Jamie Counsellor](TBD)
