# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

Instead of spending time figuring out the exact size of the image, I found that just setting the aspect ratio to 1:1 works great.

```css
.qr-image {
    aspect-ratio: 1/1;
    max-width: 250px;
    background-image: url("/images/image-qr-code.png");
    background-size: contain;
    border-radius: 5px;

}
```
## Author

- Frontend Mentor - [@FNH99](https://www.frontendmentor.io/profile/FNH99)
