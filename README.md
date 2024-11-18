# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Process Summary](#process-summary)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [https://github.com/cookie-monster01/social-links.git]
- Live Site URL: [https://vercel.com/cookie-monster01s-projects/social-links]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### Process Summary

Social-links profile is made as a card inside an article element. I have used two divs inside the article to style and center the social-links profile card. 

On the card div I have applied flexbox to center the container div. And on the container div I have applied grid layout. 
(Note: I checked if I can interchange the application of the two layouts, and I also checked if I could use only one layout on both divs either flexbox or grid layout to see if it has any impact. As I did not notice any difference, I chose to apply both flexbox and css grid.)

I have used width and max-width to control the width of the container div. I have also used calc on both inline and block padding on the container to increase the padding on bigger screen (Could i do this differently? What would be the best practice here?).  

I have used media queries on the screen-sizes between 48em and 62em to replicate the design style. 
Between these sizes I have increased the width, inline and block padding on the container div. 


### Continued development

Calc on inline and block padding of the container, could I increase the padding in any other way for bigger screen sizes?

## Author
- Frontend Mentor - [@cookie-monster01]
