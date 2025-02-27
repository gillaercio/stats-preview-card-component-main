# stats-preview-card-component-main
 stats-preview-card-component-main

This is a solution to the [Stats-preview-card-component-main challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

These are my screenshots showing how the project turned out.

- For desktop version:

Desktop 1024px
![design](./assets/images/screenshot-desktop1.png)

Desktop 1440px
![design](./assets/images/screenshot-desktop2.png)

- For mobile version:

![design](./assets/images/screenshot-mobile.png)

### Links

- Solution URL: [My Solution](https://gillaercio.github.io/stats-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Grid Layout
- Mobile-first workflow

### What I learned

I took advantage of this project to practice the use of **Grid Layout** and **Media queries**:

Simple use of grid-template-columns

```css
#content {
    width: 896px;
    grid-template-areas: 
    "info image";
    transition: width .4s, height .4s;
    transition-timing-function: ease;
  }

  .info {
    grid-area: info;
    width: 448px;
    padding: 60px;
  }

  .feature-img {
    grid-area: image;
    background-image: url(../images/image-header-desktop.jpg);
    width: 448px;
    height: 440px;
  }
```

### Continued development

I would like to improve the use of **Grid layout** in conjunction with media queries.

## Author

- Frontend Mentor - [@gillaercio](https://www.frontendmentor.io/profile/gillaercio)
- Github - [My Github](https://github.com/gillaercio)
- LinkedIn - [My LinkedIn](https://www.linkedin.com/in/gildman-la%C3%A9rcio/)