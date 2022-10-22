# Frontend Mentor - Product Preview Card Component Solution
This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa) created by [@jeniDub](https://github.com/jenidub). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents
- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshots](#screenshot)
  - [Project Links](#links)
- [My Process](#my-process)
  - [Project Tech Stack](#built-with)
  - [What I Learned](#what-i-learned)
  - [Resources Used](#useful-resources)
- [Author Info](#author)

## Overview
The goal of this project was to create a responsive design for a product preview card that works on desktops (width 1440px) and mobile devices (up to 415px - size of iPhone devices).
### The Challenge
Users should be able to:
- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshots
![Desktop Screen View](./images/image-product-desktop.jpg)
![Mobile Screen View](./images/image-product-mobile.jpg)
### Project Links
- [Solution URL](https://github.com/jenidub/product-preview-card)
- [Live Site URL](https://jenidub.github.io/product-preview-card/)

## My Process
I chose to begin by designing the mobile version of the site since it is the most restrictive. I structured the HTML file first to optimize the CSS styling. I then followed the styleguide provided to style according to the Product team's specs. After a thorough review of the site, I made the necessary transitions to the desktop view using the media query feature and responsive design principles.
### Project Tech Stack
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I Learned
The project gave me a lot of practice using **Flexbox** because it required multiple flexbox arrangements within each view and to make the transition between mobile and desktop views. I also learned to not **repeat property-value pairs** if they are the same in different views. 

For example, here is the CSS rule for the **#ad-container**:

*Desktop View*
`#ad-container {
  background-color: hsl(30, 38%, 92%);
  display: flex;
  justify-content: center;
  flex-direction: row;
  align-items: center;
  height: 700px;
  width: 1000px;
  padding: 20px;
}`

*Mobile View*
`@media screen and (max-width: 415px){...
  #ad-container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 0px;
    height: 80%;
}`

### Resources Used
- Website - [CSS-Tricks Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- Website - [W3Schools HTML Reference Guide](https://www.w3schools.com/html/)

## Author Info
- Frontend Mentor - [@jenidub](https://www.frontendmentor.io/profile/jenidub)
- GitHub Page - [@jenidub](https://github.com/jenidub)
