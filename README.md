# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot
![image](https://user-images.githubusercontent.com/85772081/141669266-01743961-583b-403f-8670-f38d54fdb711.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Center a div and use an overlay to change the image color.

```css
.proud-of-this-css {
    position: absolute; /*Can also be `fixed`*/
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    margin: auto;
    /*Solves a problem in which the content is being cut when the div is smaller than its' wrapper:*/
    max-width: 90%;
    max-height: 80%;
    overflow: auto;
}
```

```css
.proud-of-this-css {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: hsl(277deg 96% 51% / 51%);
}
```

### Continued development

Focus on studying CSS Grid, Flexbox and Responsive Design.

## Author

- Name - [Adrián Ramírez](https://www.your-site.com)
- Frontend Mentor - [@adrian-rmz](https://www.frontendmentor.io/profile/adrian-rmz)
- Twitter - [@adrian-rmz](https://github.com/adrian-rmz)
