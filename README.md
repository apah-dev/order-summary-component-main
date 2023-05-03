# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/apah-dev/order-summary-component-main.git)
- Live Site URL: [Add live site URL here](https://apah-dev.github.io/order-summary-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Learnt when to use fixed widths using rem to prevent the increasing width caused by using percentages on width.

```css
main {
  display: flex;
  flex-direction: column;
  text-align: center;
  width: 25rem;
  margin: 100px auto;
  box-shadow: 0rem 1rem 1rem 1rem hsla(224, 23%, 55%, 0.2);
  border-radius: 1rem;
}

@media (max-width: 48rem) {
  main {
    width: 22rem;
    background-image: url(images/pattern-background-mobile.svg);
    background-repeat: no-repeat;
    background-size: contain;
  }

  p {
    font-size: 0.8rem;
  }

  body {
    padding-left: 1rem;
    padding-right: 1rem;
  }
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

### Useful resources

- [PIXEL TO REM CONVERTER](https://nekocalc.com/px-to-rem-converter) - This helped me for converting from pixel to rem for my width and media queries.

## Author

- Frontend Mentor - [@apah-dev](https://www.frontendmentor.io/profile/apah-dev)
- Twitter - [@benson_apah](https://www.twitter.com/benson_apah)

## Acknowledgments

For converting px to rem
