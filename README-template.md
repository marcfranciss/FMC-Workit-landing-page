# Frontend Mentor - Workit landing page solution

This is a solution to the [Workit landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/workit-landing-page-2fYnyle5lu). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![Full page (1440px)](./starter-code/Screenshot%202024-02-06%20at%2018-34-32%20Frontend%20Mentor%20Workit%20landing%20page.png)

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

I learned to create curved border and merging two background colors. Also, i learned the using of 'background-image: url()' for selected background patters.

To see how you can add code snippets, see below:

```html
<main>
  <header>
    <div class="heading-large">Data <span class="style-underline">tailored</span> to your needs.</div>
    <button class="primary-default">Learn more</button>
  </header>  
  </main>
```
```css
main:before {
    content: "";
    z-index: 1;
    position: absolute;
    background-color: #24053E;
    border-radius: 0% 0% 150% 150%/0% 0% 40% 40%;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    background-image: url(./assets/images/bg-pattern-1.svg), url(./assets/images/bg-pattern-2.svg);
    background-position: -135px top, right -50px center;
    background-repeat: no-repeat;
}


## Author

- Website - [Marc Francis](https://marcfranciss.github.io/)
- Frontend Mentor - [@marcfranciss](https://www.frontendmentor.io/profile/marcfranciss)


