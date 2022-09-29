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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop](./src/imagens/screenshot-desktop.png)
![Mobile](./src/imagens/screenshot-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I learned how to work with the tag <picture>

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

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
