# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building real projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Build out the project to the designs provided

![Desktop preview of the project](./design/desktop-preview.jpg)

### Screenshot

![Screen shot on desktop](./images/screenshot-desktop.png)

![Screen shot on mobile](./images/screenshot-iphone8.png)


### Links

[Link to gitpage](https://edwardnguyen225.github.io/front_end_mentor/profile-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

When adding the background, I found it hard to position the SVG file, as it doesn't stay in the place I want it to be. But then, as a reference to [Zextis's solution](https://github.com/zextis/profile-card-component), it would be easier to position by using the calc function. The code of the background is shown below:

```css
  background: url(/images/bg-pattern-top.svg) calc((50vw - 100vh)) -50vh,
    url(/images/bg-pattern-bottom.svg) 50vw 50vh;
  background-size: auto 100vh;
  background-repeat: no-repeat;
  background-color: $darkCyan;
```

## Author

- Frontend Mentor - [@edwardnguyen225](https://www.frontendmentor.io/profile/edwardnguyen225)
- Facebook - [@trinhan.vn](https://www.facebook.com/trinhan.vn/)

## Acknowledgments

I must give a hat tip to [Zextis](https://github.com/zextis), whose solution really helped me in editing the background.
