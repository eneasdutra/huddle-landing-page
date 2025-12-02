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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

The project consists of a pricing grid component with a fully responsive layout and clean design, simulating a subscription plan section.

It demonstrates best practices in HTML structuring, use of CSS variables, and layout adaptation for different screens.

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](/images/Screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://eneasdutra.github.io/huddle-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

During this challenge, I consolidated some important concepts:

1. Fluid responsiveness using Flexbox.

2. Semantic organization of HTML, improving accessibility.

3. Use of CSS variables for consistency in colors and spacing.

4. Adaptive layout with rounded borders, soft shadows, and balanced typography.

To see how you can add code snippets, see below:

To see how you can add code snippets, see below:

```html
<header class="logo-and-illustration">
  <img src="images/logo.svg" alt="Huddle logo" class="logo">
  <div class="illustration-container">
    <img src="images/illustration-mockups.svg" alt="Huddle UI Mockups" class="mockup-img">
  </div>
</header>
```
```css
.logo-and-illustration {
    text-align: left;
}
.logo {
    max-width: 120px;
    margin-bottom: 4rem;
}
.illustration-container {
    margin-bottom: 2rem;
}
```
### Continued development

Planned improvements:
- Add subtle entrance and hover animations.
- Implement the same layout using React Components.
- Apply BEM methodology to standardize CSS class naming.

### Useful resources

- 🧱 Guia de CSS – MDN
- 🎨 Frontend Mentor Style Guide
- 📘 The Markdown Guide
- ⚙️ CSS Tricks – Complete Guide to Flexbox  

## Author

- Github - [eneasdutra](https://github.com/eneasdutra)
- Frontend Mentor - [@eneasdutra](https://www.frontendmentor.io/profile/eneasdutra)
- LinkedIn - [@eneasmdutra](https://www.linkedin.com/in/eneasmdutra/)  [![LinkedIn](https://img.shields.io/badge/-LinkedIn-%230077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eneasmdutra/)

## Acknowledgments

I am grateful to the Frontend Mentor community for the inspiration, feedback, and constant support.
Each challenge is a new opportunity to evolve as a learner in front-end development.
