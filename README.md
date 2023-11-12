# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Process](#process)
  - [HTML](#html)
- [Author](#author)


## Overview

### Screenshot

![](https://github.com/FNH99/qr-code-component-main/blob/main/images/screenshot.png)

### Links

- Live Site URL: (https://qr-code-component-main-self-alpha.vercel.app)

## Process

### HTML

Starts with base html template, vscode gives basic html template by typing '!' and add the page title within "title":

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>QR code component</title>
</head>
<body>
  
</body>
</html>
```

In the "head" element, add the link to the stylesheet for CSS:

```html
<link rel="stylesheet" href="style.css">
```

To embed a font from google font such as https://fonts.google.com/specimen/Outfit, copy the code to the "head":

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Outfit" rel="stylesheet">
```

Within the "body" add the "main" element to contain the page:
```html
<main>

</main>
```

from now the code will continue within the "main" element. Make a "div" to contain the image and the other text and set its class:
```html
<div class="container">

  </div>
```

Inside this 'container' will be the main content of the page, add another "div" and set the class to contain the image:
```html
<div class="qr-image">
        <img src="/images/image-qr-code.png" alt="QR Code linking to Frontend Mentor challenges">
</div>
```

'src' will specify where the page will find the image, the 'alt' attribute gives the image an alternate text if the image cannot be displayed.

Still within the 'container', make an "article" element where the text resides. "h1" will be the most important text, and "p" would be the paragraph under it.

```html
  <article>
    <h1>Improve your front-end skills by building projects</h1>
      <p>
        Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
      </p>
  </article>
```

## Author

- Frontend Mentor - [@FNH99](https://www.frontendmentor.io/profile/FNH99)
