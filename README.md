# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Solution Code](https://github.com/Yash-devasp/nft-card)
- Live Site URL: [Github Pages Here](https://yash-devasp.github.io/nft-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

With this code I was able to understand how the peudo classes and pseudo elements work. How we can change properties and create amazing effects.

To create the hover effect on image, see below:

```html
<div class="main-img"></div>
<div class="active-state"></div>
```
```css
.active-state {
  display: none;
}
.main-img:hover .active-state {
  display: block;
}
```

### Continued development

I will be focusing on layouts and how to improve my structuring of code. Also I would be working on responsive website development.

## Author

- Frontend Mentor - [@Yash-devasp](https://www.frontendmentor.io/profile/Yash-devasp)
- Twitter - [@YashGos51892893](https://twitter.com/YashGos51892893)

## Acknowledgments

I am helpful for the wornderful community on frontend mentor to push me to complete my project.
