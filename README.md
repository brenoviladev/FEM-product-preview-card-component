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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/product-preview-card-component-_IgMJdn-90)
- Live Site URL: [Product preview card component](https://brenoviladev.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Sass

### What I learned

I learned how to use basic media queries and basic sass features

```css
@media screen and (min-width: 450px) {
  .container {
    display: flex;
    max-width: 600px;
    margin: auto;
    margin-top: 50px;
  }
  .inner-container{
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    width: 236px;
    padding: 32px;
  }
  .product-image {
    background-image: url("./images/image-product-desktop.jpg");
    width: 300px;
    height: 500px;
    border-radius: 10px 0 0 10px;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
  }
}
```

### Continued development

I'll focus on using media queries and practicing Sass.

## Author

- Website - [Breno Vila](https://brenoviladev.github.io/homepage/)
- Frontend Mentor - [@brenoviladev](https://www.frontendmentor.io/profile/brenoviladev)
- LinkedIn - [Profile](https://www.linkedin.com/in/breno-vila-dev/)