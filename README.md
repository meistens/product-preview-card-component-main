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

The design is as close to the original. Some screen width of some recent devices from 414px up to 428px and some devices with widths of 320px (specifically iPhone 11, 12 Pro Max and some older devices).

### Screenshot

![Mobile](./Finished%20designs/iphone-12-6.1-1170x2532.png)

![Tablet](./Finished%20designs/ipad-pro-12.9-2048%20x%202732.png)

![Laptop](./Finished%20designs/11-inch-macbook-air-0-1366%20%C3%97%20768.png)

![Desktop](./Finished%20designs/desktop-1600x900-0-1600%20x%20900.png)

### Links

- Solution URL: [Add solution URL here](https://productpage-blue.vercel.app)
- Live Site URL: [Add live site URL here](https://productpage-blue.vercel.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- sass

### What I learned

```html
<picture>
  <source
            media="(min-width: 501px)"
            srcset="./images/image-product-desktop.jpg"
          />
</picture>
```

### Continued development

Targeting devices with slightly off design will be considered.

### Useful resources

- [As ever, MDN](https://www.developer.mozilla.org) - Looked up options on how to use multiple images without resorting to background fixes, found the picture element.

## Author

- Frontend Mentor - [@meistens](https://www.frontendmentor.io/profile/meistens)
- Twitter - [@meistenz](https://www.twitter.com/meistenz)
