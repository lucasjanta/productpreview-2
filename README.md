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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop](./src/imagens/screenshot-desktop.png)
![Mobile](./src/imagens/screenshot-mobile.png)

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/product-preview-using-html-and-css-PZ7-WkWUxp)
- Live Site URL: [Github Pages](https://lucasjanta.github.io/productpreview-2/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I learned how to work with the tag picture

```html
<picture>
  <source media="(min-width:769px)" srcset="./src/imagens/image-product-desktop.jpg">
  <source media="(max-width:768px)" srcset="./src/imagens/image-product-mobile.jpg">
  <img src="./src/imagens/image-product-desktop.jpg" style="width:auto;height:100%;">
</picture>
```

## Author

- Frontend Mentor - [@lucasjanta](https://www.frontendmentor.io/profile/lucasjanta)
- Twitter - [@lucasjanta](https://www.twitter.com/lucasjanta)