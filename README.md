# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
Create a responsive grid- based layout. The layout should:
-Include eight sections 
- Be responsive for different screen sizes.

### Screenshot

![](/preview.jpg)


### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/responsive-bento-grid-AyKilYzTRl)
- Live Site URL: [Live Demo](https://frontend-bento-grid.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Google Fonts

### What I learned

During this project, I got the chance to learn about different CSS grid properties like:
* grid-template-areas: Simplifies complex layouts by defining named grid regions.
* Media quries to make the designs responsive based on the device used.

Code snippets, see below:

```css
.bento {
    display: grid;
    gap: 2rem;
    grid-auto-columns: 1fr;
    grid-template-areas:
        'box1 box2 box2 box3'
        'box1 box2 box2 box3'
        'box1 box2 box2 box3'
        'box1 box2 box2 box3'
        'box1 box5 box6 box3'
        'box4 box5 box6 box3'
        'box4 box5 box6 box3'
        'box4 box7 box8 box8'
        'box4 box7 box8 box8'
        'box4 box7 box8 box8';
}
```


### Continued development
In future projects, I aim to use and explore advanced CSS grid techniques.

### Useful resources

- [Odin Project](https://www.theodinproject.com) - This helped me eith detail guide of CSS.
- [MDN Web Docs:CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout) - This is an amazing guide with details of CSS grid.

## Author

- Website - [Anelda & Moses](https://frontend-bento-grid.netlify.app/)
- Frontend Mentor - [@ladyanelda](https://www.frontendmentor.io/profile/yourusername)


## Acknowledgments

Thanks to Frontend Mentor for providing this challenge.
