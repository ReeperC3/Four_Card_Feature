# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

![](/images/127.0.0.1_5500_index.html.png)

### Links

- Solution URL: [Github](https://github.com/reeperc3/Four_Card_Feature)
- Live Site URL: [Github Pages](https://reeperc3.github.io/Four_Card_Feature)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- SCSS / SASS

### What I learned

This was my first time attempting a mobile-first workflow and to be honest, I can see why people like it. I also did some more work with CSS grid, media queries and SCSS/SASS.

```css
@media only screen and (min-width: 1200px) {
    .card-container {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        grid-template-areas: 
            "cyan red blue"
            "cyan orange blue";
        align-items: center;
        justify-content: center;
    }
}
```

### Useful resources

- [95 Beautiful CSS shadow-box examples - CSS Scan](https://getcssscan.com/css-box-shadow-examples) - Helpful website for getting some nice looking shadow-box examples for CSS.
