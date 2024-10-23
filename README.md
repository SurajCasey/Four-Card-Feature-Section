# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I have learned to place the cards using grid method, it was an easy way to do this challenge.

To see how you can add code snippets, see below:

Style.css
.container2{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: auto auto;
    grid-template-areas: 
    "supervisor team calculator"
    "supervisor karma calculator"; /*layout structure for boxes*/
    place-items: center;
    gap: 2rem;
}


### Continued development

I would like to learn a lot about about css flexbox, grid and positioning to be good at design.

### Useful resources

- [CSS Grid](https://www.w3schools.com/css/css_grid.asp) - This helped me for structuring my gird for the cards. I really liked this pattern and will use it going forward.


## Author
- Frontend Mentor - [@SurajCasey](https://www.frontendmentor.io/profile/SurajCasey)
- Linkedin - [@SurajKhatri](https://www.linkedin.com/in/surajkhatri445/)



## Acknowledgments
I acknowledge frontend mentor community for helping me to flourish my frontend skills. In any problems they have provided me with the solutions.
