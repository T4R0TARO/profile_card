# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Planning out the how I was going to tackle the design, I knew that I would have to use a css card effect with a layout similar to a header/body/footer/ style. So I start off my project organizing my html and come up with resusable class names. 

After the html is organized I begin with some broiler plate css; base styles, custom properties, and font-style to have spacing and calling custom variables easier.

Next I position the the containers of the content to the center of the page and begin styling my css.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This project tested my understanding of the concepts of flex-box and how to manipulate flex-items to behave the way we intended. 
There were various times where I would have to change an element into a flex-container in-order to positon them items to be displayed vertically or horizontally.

The syntax below targets the footer of the card in an attempt to position the flex-items to be centerd within its flex-container and to have the flex-items evenly sized and spaced. 

flex is the shorthand for flex-grow and flex-shrink and by giving the flex-items a felx: 1 the items will fill up the available space evenly and will adjust to the width of the browser. 

.card_footer .item {
``` 
    display: flex;
    flex: 1;
    height: 100px;
    flex-direction: column;
    justify-content: center;
    align-items: center;

```
}


### Continued development

I will continue to familiarize myself with flex-box concept. Later maybe add animation to the background img.

### Useful resources

- [MDN Web Doc](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-grow) - This helped me have a better understanding of flex-grow and flex-shrink concepts and the how to implement them into my project.
- [MDN Web Doc_Cookbook](https://developer.mozilla.org/en-US/docs/Web/CSS/Layout_cookbook/Center_an_element) - Whenever I forgot something very basic.


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@T4R0TARO](https://www.frontendmentor.io/profile/T4R0TARO)
- Twitter - [@taro_code](https://www.twitter.com/taro_code)




