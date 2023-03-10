# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](/images/product-preview-screenshot.png)

### Links

- Solution URL: [Repository](https://github.com/SabrinaY123/Product-Preview-Component)
- Live Site URL: [Demo](https://product-preview-sy.netlify.app/)

## My process

I started with building a flexbox to position my image and product description. I made sure to center this flexbox with another <div> I named #home-page by using display:flex properties. I used a desktop-first workflow so I focused on the margin, padding and layout of each element with a bigger viewscreen. Based on the jpg of the desktop design I estimated the width and height and worked around that. Once completed, I found my screen breakpoint to be when my flexbox started to "fall apart" and set a media query for that number to be my max-width. Then my flexbox changed from flex-direction:row to flex-direction:column and I did the same process by basing the new margins and padding on the jpg of the mobile design.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned more about flexbox and media queries when designing the mobile and desktop views of this project. I also explored more about the css element "object-fit" and how it works!

### Continued development

In the future I would work on more projects with a mobile-first workflow compared to desktop-first to see if that would be more effective. I also will work on more practice with flexbox and CSS Grid to ensure I can fully comprehend these concepts.

## Author

- Website - [Sabrina Yohannes](https://www.sabrinay123.github.io/Personal-Site/)
- Frontend Mentor - [@SabrinaY123](https://www.frontendmentor.io/profile/SabrinaY123)
- Discord - [@SabrinaY#5407](https://discord.com/)


## Acknowledgments

Youtube Instructors & Angela Yu on Udemy! I can't thank them enough! 