# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot of the project](./design/destkop-design.jpg)
*Desktop view*

![Screenshot of the project](./design/mobile-design.jpg)

*Mobile view*

### Links

- Solution URL: [GitHub Repo](https://github.com/Mawuawoe/Frontend_projects/tree/main/social-links-profile-main)
- Live Site URL: [Live Demo](https://frontend-projects-blogcard.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (variables)
- Flexbox
- Mobile-first workflow
- [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)

### What I learned

This project helped reinforce my understanding of:
- Centering elements using Flexbox
- Creating uniform clickable areas using consistent width and padding
- Styling links to behave like buttons with hover/active states
- Using `white-space: nowrap` to prevent link wrapping
- Writing cleaner, responsive HTML/CSS with a mobile-first approach.

```css
.link {
    white-space: nowrap;
    width: 90%;
    background-color: hsl(0, 0%, 20%);
    padding: 1rem;
    text-align: center;
    border-radius: 0.5rem;
    color: white;
    text-decoration: none;
    font-weight: 600;
    transition: background-color 0.3s ease;
}

.link:active {
  background-color: hsl(75, 94%, 57%);
  color: hsl(0, 0%, 8%);
}
```

## Author

- GitHub – [@Mawuawoe](https://github.com/Mawuawoe)
