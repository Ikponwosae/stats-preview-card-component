# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshots

- Mobile Version

![](./images/screenshot-mobile.png)


- Desktop Version

![](./images/screenshot-desktop.png)


### Links

- Solution URL: [https://github.com/Ikponwosae/stats-preview-card-component](https://github.com/Ikponwosae/stats-preview-card-component)
- Live Site URL: [https://stats-preview-card-component-ikponwosae.vercel.app/](https://stats-preview-card-component-ikponwosae.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

- How to declare css variables in the :root selector.
- How to use css variables with the var() function.
- How to use media queries to make a site responsive.
- How to change the order of css grid columns with grid template areas.


```css
.card-container{
  box-sizing: border-box;
  height: 420px;
  margin-top: 10px;
  margin-bottom: 10px;
  margin-left: 10px;
  margin-right: 10px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-areas: "column-1 column-2";
}

.card-container div:nth-child(1){ grid-area: column-2; }

.card-container div:nth-child(2){ grid-area: column-1; }
```

### Continued development

- Flexbox
- Css Grid


### Useful resources

- [Create an image with a colour overlay in css](https://dev.to/ellen_dev/two-ways-to-achieve-an-image-colour-overlay-with-css-eio) - This really helped me. I really liked this pattern and will use it going forward.


## Author

- Frontend Mentor - [@ikponwosae](https://www.frontendmentor.io/profile/ikponwosae)
- Twitter - [@neneecodes](https://www.twitter.com/neneecodes)
- Medium - [@ikponwosae](https://medium.com/@ikponwosae)
