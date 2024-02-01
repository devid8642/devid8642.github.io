# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.png)


### Links

- [Solution URL:](https://your-solution-url.com)
- [Live Site URL:](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Media Queries

### What I learned

Use variables in CSS to organize the project's color palette:

```css
...
:root {
    --nutmeg: hsl(14, 45%, 36%);
    --dark_raspberry: hsl(332, 51%, 32%);
    --white: hsl(0, 0%, 100%);
    --rose_white: hsl(330, 100%, 98%);
    --eggshell: hsl(30, 54%, 90%);
    --light_grey: hsl(30, 18%, 87%);
    --wenge_brown: hsl(30, 10%, 34%);
    --dark_charcoal: hsl(24, 5%, 18%);
}
...
```

Use the object-fit property to make images occupy all the available space without distorting them:

```css
...
.omelet-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 0;
    border-top-right-radius: 2rem;
    border-top-left-radius: 2rem;
}
...
```

Using the ::marker pseudo element to style only list markers:

```css
...
.preparation-list-item::marker {
    color: var(--dark_raspberry);
}
...
.ingredients-list-item::marker, .instructions-list-item::marker {
    color: var(--nutmeg);
}
...
```

## Author

- Website - [Dêvid Teófilo](https://devid8642.github.io)
- Frontend Mentor - [@devid8642](https://www.frontendmentor.io/profile/devid8642)