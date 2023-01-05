# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- Build out the project to the designs provided

### Screenshot

![](./screenshot_desktop.png)
![](./screenshot_mobile.png)

### Links

- Solution URL: [on Frontend Mentor](https://www.frontendmentor.io/solutions/profile-card-component-lNpTOSUYhY)
- Live Site URL: [on Github](https://PYkm.github.io/profile-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The most challenging part is to combine multiple background image together, and change their position. I'm using code snippets as below:

```css
body{
  background: no-repeat right 45vw bottom 50vh / auto 120% url(../images/bg-pattern-top.svg),
              no-repeat left 45vw top 50vh / auto 120% url(../images/bg-pattern-bottom.svg),
              var(--main-bg-color);
}
```

### Continued development

Technique that I'm not completely familiar with, can be found in this challenge:
- Use `font` and  `background` shorthand instead longhand properties.
- Show multiple `background-image` for a single element.

Technique that I found useful, although not using in this challenge:
- SASS

### Useful resources

- [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html) - This helped me to understand what are the best practices when coding html and css, under Google's suggestion.
- [background-position on MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/background-position) - This is an amazing article which helped me finally understand the percentage used in `background-position`. I'd recommend it to anyone still learning this concept.

## Author

- Website - [PYkm](https://pykm.github.io/)
- Frontend Mentor - [@PYkm](https://www.frontendmentor.io/profile/PYkm)
