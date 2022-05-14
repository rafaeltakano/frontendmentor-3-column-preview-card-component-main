# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://rafaeltakano.github.io/frontendmentor-3-column-preview-card-component-main/](https://rafaeltakano.github.io/frontendmentor-3-column-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Sass](https://sass-lang.com/) - For styles

### What I learned

I learned that I can use media queries inside a class

```css
.container {
  display: grid;
  grid-template-columns: auto;
  grid-template-rows: repeat(3, 1fr);
  justify-items: center;
  margin-inline: auto;
  max-width: 60rem;

  @media (min-width: 65em) {
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: auto;
  }
}
```

## Author

- LinkedIn - [Rafael Takano](https://www.linkedin.com/in/rafaeltakano1/)
- Frontend Mentor - [@rafaeltakano](https://www.frontendmentor.io/profile/rafaeltakano)
