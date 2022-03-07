# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

I enjoyed this challenge. It really tested me in areas that I wasn't expecting, but I'm glad it did because I know I'm better for it. My main goal with this challenge was to test my knowledge on using flexbox especially with mobile responsiveness. I feel my result is highly similar to the challenge design.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Live Site URL: (https://your-live-site-url.com)

## My process

I started with the background colors as those would help me with seeing my layout. Then, I moved to the actual layout of all the pieces. After I had the layout how I wanted it and the sizing of everything close to the example, I then moved on to all of the styling components. I saved the buttons for last.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media query for mobile responsiveness

### What I learned

This challenge tested me on using flexbox. I hadn't really used it before except in coding practices. There is a lot with flexbox that I still don't know, which was apparent in this challenge. For instance, the background colors of each flex item were overflowing the flex container. I had to learn how to hide that overflow.

I also learned that pixels vs. percentages changes how the border-radius of an element will look. I hadn't learned that before, but I'm glad I know now for the future.

See code snippets below:

```css
.container {
  display: flex;
  width: 60vw;
  margin: 100px auto 0;
  border-radius: 5px;
  overflow: auto;
}
```

### Continued development

I know I could still use more practice with flexbox; again, it's apparent that there is still a lot I don't know.

I also tried to better refactor my code so I wasn't repeating code and so the structure made sense for someone else looking at it. I'm sure there are better practices I could do to help with code refactoring.

Like with the last challenge I did, this challenge showed me that I could use more practice with using different properties to help better position elements.

### Useful resources

- [MDN Docs](https://developer.mozilla.org/en-US/docs/Web) - MDN helped me with better understanding the flexbox, especially when it came to my issue with overflow.
- [W3Docs](https://www.w3docs.com/) - W3Docs helped me with figuring out how to change the cursor to a pointer when hovering over the buttons.

## Author

- Chanel Marshall
- Frontend Mentor - [@chanelmarshall](https://www.frontendmentor.io/profile/chanelmarshall)
