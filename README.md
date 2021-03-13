# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./design/desktop-preview.jpg)

### Links

- Solution URL: [@Github](https://github.com/gustavosanchezgalarza/frontend-mentor-testimonials-grid-section)
- Live Site URL: [@Vercel](https://frontend-mentor-testimonials-grid-section-gusanchedev.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Media queries
- Background images

### What I learned

Key learnings from this project:

- Using multiple CSS files in HTML document for adjusting content to media queries
```html
    <link rel="stylesheet" href="./css/mobile.css" />
    <link
      rel="stylesheet"
      media="screen and (min-width:768px) and (max-width:1023px)"
      href="./css/tablet.css"
    />
    <link
      rel="stylesheet"
      media="screen and (min-width:1024px)"
      href="./css/desktop.css"
    />
```
- Using background images and adjusting position
```css
article:nth-of-type(1) {
  background-color: var(--moderate-violet);
  background-image: url("../images/bg-pattern-quotation.svg");
  background-repeat: no-repeat;
  background-position: top 0px right 20px;
}
```


### Continued development

Another challenges will be added wo improve my HTML/CSS/JS development skills taken from [FrontendMentor.io](https://www.frontendmentor.io/challenges).

Plese see other challenges solved by me in my Github [site](https://github.com/gustavosanchezgalarza).

### Useful resources

- [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This is a awesome resource fo understanding CSS Grid.

## Author

- Website (Coming soon!) - [Gustavo Sanchez](https://www.gusanche.dev)
- Frontend Mentor - [@gustavosanchezgalarza](https://www.frontendmentor.io/profile/gustavosanchezgalarza)
- Twitter - [@gusanchedev](https://www.twitter.com/gusanchedev)


**Thanks for reading me 👍**

**Gustavo**
