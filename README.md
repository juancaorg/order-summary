# Frontend Mentor - Order Summary Card

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [GitHub Respository](https://github.com/juancaorg/order-summary-card)
- Live Site URL: [ordersummarycard.juanca.dev](https://ordersummarycard.juanca.dev)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This one was easy in comparison to other card projects. I struggled a little bit centering the items on my body CSS grid and ignoring the `pattern-background`.

Could figure out a solution by centering all the items in the body grid, and then centering the `pattern-background` back. Just like the following:

```css
body {
  min-height: 100vh;
  font-family: "Red Hat Display", sans-serif;
  background-color: var(--pale-blue);
  display: grid;
  align-items: center;
}

/* 
 * Move the pattern-background back.
 * Every other items is still centered after this.
*/

.pattern-background {
  display: grid;
  align-items: center;
}
```

## Author

- Website - [juanca.org](https://www.juanca.org)
- Frontend Mentor - [@juancaorg](https://www.frontendmentor.io/profile/juancaorg)
- Twitter - [@juancaorg](https://twitter.com/juancaorg)

## Acknowledgments

Thanks to [@elaineleung](https://github.com/elaineleung) for [her feedback on my solution](https://www.frontendmentor.io/solutions/order-summary-card-built-using-css-grid-and-flexbox-pKkUnA8dc5#comment-6316ee9accfc3660d9a81adc): use the [`background-image`](http://developer.mozilla.org/en-US/docs/Web/CSS/background-image) instead of a `picture` element for this challenge.
