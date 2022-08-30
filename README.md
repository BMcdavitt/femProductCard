# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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


## Overview

This is my second submission to the Front End Mentor program.  This is the first that requires a responsive display.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/screenshot-desktop.png)



### Links

- [Solution URL](https://github.com/BMcdavitt/femProductCard)
- [Live Site URL](https://bmcdavitt.github.io/femProductCard/)

## My process

### Built with

- CSS custom properties
- Flexbox

### What I learned

I implemented @media queries to control the layout.  Not for the first time, but it's been a while.
I also used CSS instead of Javascript to change the button background on hover


```css
@media screen and (max-width: 500px) {
  .productDesktopImage {
    display: none;
  }

  main {
    flex-direction: column;
  }
}

.addButton:hover {
  background-color: hsl(158, 80%, 22%);
}
```




### Continued development

I'd like to focus on mobile first development

### Useful resources

- [Example resource 1](https://www.w3schools.com/cssref/sel_hover.asp) - This showed me how to use css to react to a mouse hover event
