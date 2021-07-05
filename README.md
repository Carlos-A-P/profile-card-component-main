# 3-column preview card component

- Live website -(https://carlospwd-profile-card-component.netlify.app/)

## Table of contents

- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](img/Profile card Desktop image - final product.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

What was most difficult for me was the background image and setting up the positions correctly, I wasn't sure to why there were two images at first but I later learned that I can set two images as a background image. I also learned how to use the background positions property for both images and then how to use viewport units.

```css
body {
	background-image: url(../images/bg-pattern-top.svg),
		url(../images/bg-pattern-bottom.svg);
	background-repeat: no-repeat, no-repeat;
	background-position: right 50vw bottom 50vh, left 50vw top 50vh;
	background-color: hsl(185, 75%, 39%);
}
```

### Continued development

I thought this was going to be a simple challenge but the background image really proved to be a little tricky. I want to continue learning about positions of elements and how to positions items accurately

### Useful resources

- [background-position](https://developer.mozilla.org/en-US/docs/Web/CSS/background-position) - This helped me understand how to use background positions

## Author

- Website - [Carlos Perez](https://www.site.com)
- Frontend Mentor - [@Carlos-A-P](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@WDCarlosP](https://www.twitter.com/WDCarlosP)
