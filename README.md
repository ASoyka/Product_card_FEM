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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Product preview card component](./Screenshot.png)

### Links

- Solution URL: [Solution](https://github.com/ASoyka/Product_card_FEM)
- Live Site URL: [Live](https://asoyka.github.io/Product_card_FEM/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learn how to use @media query for image in HTML document using <picture> and <source> tags.

Get practice with using Flexbox and Grid layouts.

Its my first time working with design macket in Figma app.

```html
<picture class="product__image">
	<source srcset="./img/image-product-mobile.jpg" media="(max-width: 620px)">
	<img  src="./img/image-product-desktop.jpg" alt="bottle of perfume" width="300" height="450" loading="lazy">
</picture>
```

## Author

- Website - [Soyka Alexander](https://asoyka.github.io/Portfolio_FCC/)
- Frontend Mentor - [@ASoyka](https://www.frontendmentor.io/profile/MrSoyka)
- GitHub - [@ASoyka](https://github.com/ASoyka)

## Acknowledgments

- Thanks to https://www.frontendmentor.io/.