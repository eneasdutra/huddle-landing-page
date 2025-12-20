# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/screenshot.png)

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

In this project, I reinforced the use of **CSS Custom Properties** to manage HSL colors and how to structure a responsive layout that drastically switches between mobile and desktop using Flexbox.

Example of how I managed HSL colors in the root directory:
```css
:root {
  --violet: hsl(257, 40%, 49%);
  --soft-magenta: hsl(300, 69%, 71%);
  --white: hsl(0, 0%, 100%);
}
```
I also focused on the accessibility of social media icons, ensuring that screen reader users know where the links point:
```HTML
<a href="#" aria-label="Visite nosso Facebook">
  <i class="fa-brands fa-facebook-f"></i>
</a>

### Continued development

I intend to continue exploring advanced responsive image techniques (such as using the <picture> tag) to load different background versions more efficiently, further optimizing performance.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

I thank the Frontend Mentor team for providing such inspiring designs for practice.
