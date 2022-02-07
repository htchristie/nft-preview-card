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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size;
- See hover states for interactive elements.

### Screenshot

![image](https://user-images.githubusercontent.com/84540148/152863773-e861c488-0e01-4e1a-9789-2f2e7ad0059d.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/nft-preview-card-using-flexbox-dpVLNo2BV](https://www.frontendmentor.io/solutions/nft-preview-card-using-flexbox-dpVLNo2BV)
- Live Site URL: [https://nft-preview-card-71z.pages.dev/](https://nft-preview-card-71z.pages.dev/)

## My process

### Built with

- CSS custom properties
- Flexbox

### What I learned

Through this challenge I learned how to use a ::before pseudo-element to create a custom hover state, which was something entirely new for me. 

```css
.card-img::before {
  cursor: pointer;
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  background: url(/images/icon-view.svg) no-repeat center;
  background-color: hsla(178, 100%, 50%, 0.5);
  border-radius: 5px;
  opacity: 0;
}

.card-img:hover::before {
  opacity: 1;
  transition: opacity .15s ease-in-out;
}
```

### Continued development

I had some trouble with the responsive design - I didn't quite know what I was doing, even though I had done some research beforehand. I still have a long way to go and a lot to study.

## Author

- LinkedIn: [Cristyane Tamioso](https://www.linkedin.com/in/cristyane-tamioso/)
- Frontend Mentor: [@htchristie](https://www.frontendmentor.io/profile/htchristie)
