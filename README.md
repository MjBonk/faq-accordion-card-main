# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## accordionle of contents

- [Overview](#overview)
     - [The challenge](#the-challenge)
     - [Screenshot](#screenshot)
     - [Links](#links)
- [My process](#my-process)
     - [Built with](#built-with)
- [Author](#author)



## Overview
I chose to make this challenge without javascript purely because i don't know javascript yet and it would be a fun challenge :) 
I made the accordion using radio inputs because i only wanted the accordion tabs to be open one at a time. This is because when you opened all of them at once the svgs edges were visible. The catch is that you can only (as far as i know) press the text to ”check it”/open the accordion tab. 
EDIT: I managed to do it with instead of input display: none; I put it to a opacity 0 with a 100% with and heigth; 

I also would like the accordion content height adapt to the text within it but i can't make a transition from height:0; to height:auto; 
EDIT: I figuerd it out using grid instead of height so the content goes from grid-template-rows: 0; to 1fr! :)

Its my first time working with svgs, they behaved differently than expected. So I will definitely play around more with those and also revisit this one when I have more knowledge and the energy to fix the things im not satesfied with yet :)


### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](./screenshot-desktop.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/MjBonk/faq-accordion-card-main)
- Live Site URL: [Add live site URL here](https://cute-croissant-0c9b41.netlify.app/



### Built with

- Semantic HTML5 markup
- CSS custom properties


## Author

- Website - [Maya Jerndahl]
- Frontend Mentor - [@ymjBonk](https://www.frontendmentor.io/profile/MjBonk)
