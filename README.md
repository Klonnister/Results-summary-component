# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size.
- See hover and focus states for all interactive elements on the page.

### Screenshot

![375 pixels wide screenshot](/screenshots/375px.png)
![1440 pixels wide screenshot](/screenshots/1440px.png)

### Links

- [Github](https://github.com/Klonnister/Results-summary-component)
- [Live Site](https://klonnister.github.io/Results-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

With this exercise I learned to create variables in CSS and use them.

```css
:root {
  --white: hsl(0, 0%, 100%);
}

body {
  background-color: var(--white)
}
```
I also practiced to use relative units for almost all elements.

```css
.card {
  padding: 1em;
}
```

I had to re-read how to add gradients as background.

```css
.section {
  background-image: linear-gradient(direction, black, white)
}
```


### Useful resources

- [CSS Variables](https://www.w3schools.com/css/css3_variables.asp) - This helped me to understand how to create variables and use them
- [Relative units by Kevin Powell](https://www.youtube.com/watch?v=N5wpD9Ov_To) - This video taught me a lot about Relative units. Highly recommended.
- [CSS gradients](https://www.w3schools.com/css/css3_gradients.asp) - This helped me to add gradients in CSS.


## Author

- Github - [Klonnister](https://github.com/Klonnister)
- Frontend Mentor - [Klonnister](https://www.frontendmentor.io/profile/Klonnister)
- Instagram - [Dennis Herrera](https://www.instagram.com/dennis_herrera_f/)

## Acknowledgments

First of all, thanks to Cristian, who helped me a lot while I was starting to learn how to code :D. And thanks to you for reading this out and leaving feedback for me to improve ;D.


