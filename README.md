# Frontend Mentor - Bento Grid Solution

This is a solution to the [Bento Grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- Interact with content areas, where applicable

### Screenshot

![Bento Grid Solution](./screenshot.png)

### Links

- Solution URL: [Solution on Frontend Mentor](https://www.frontendmentor.io/solutions/bento-grid-main-project-using-css-grid-PA_l0jM4G5)
- Live Site URL: [Live Site](https://bento-grid-main-lovat.vercel.app)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Styled Components](https://styled-components.com/) - For styling

### What I Learned

This project helped me improve my understanding of responsive grid layouts and CSS Grid properties. Here’s a snippet of how I set up the grid layout:

```css
.container {
  display: grid;
  height: auto;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: auto auto auto;
  grid-template-areas:
    "box1 box2 box2 box3"
    "box1 box4 box5 box3"
    "box6 box4 box5 box3"
    "box6 box7 box8 box8";
  padding: 20px;
  grid-gap: 20px;
}
```

This approach allowed me to create a visually interesting and responsive layout while maintaining the flexibility to adjust it for smaller screens.

### Continued Development

I plan to continue focusing on advanced CSS layout techniques, particularly for complex grid structures. Additionally, I want to deepen my knowledge of CSS custom properties and explore ways to optimize responsiveness.

### Useful Resources

- [CSS Tricks - A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This guide helped clarify various aspects of CSS Grid and was an invaluable resource throughout this project.
- [MDN Web Docs - Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design) - This article provided insights into responsive design principles and techniques.

## Author

- Frontend Mentor - [@dukeofhazardz](https://www.frontendmentor.io/profile/dukeofhazardz)
- Twitter - [@nnaemekaxjohn](https://www.twitter.com/nnaemekaxjohn)

## Acknowledgments

A big thanks to the Frontend Mentor community for the files and assets, which helped me refine my approach to this project.
