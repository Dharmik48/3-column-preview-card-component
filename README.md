# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover states for interactive elements

### Screenshot

![](./screenshots/desktop)
![](./screenshots/mobile)

### Links

- Live Site URL: [https://dharmik48.github.io/3-column-preview-card-component/](https://dharmik48.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The :nth-child property is awesome!! It helps in reducing unnecessary class in HTML.

```css
.card:nth-child(1) {
  background-color: var(--bright-orange);
}
.card:nth-child(2) {
  background-color: var(--dark-cyan);
}
.card:nth-child(3) {
  background-color: var(--very-dark-cyan);
}
```

### Continued development

The :nth-child is real handy so definitly be using in future works.

```css
element:nth-child(n) {
  property: value;
}
```

## Author

- Github - [Dharmik48](https://github.com/Dharmik48)
- Frontend Mentor - [@Dharmik48](https://www.frontendmentor.io/profile/Dharmik48)
