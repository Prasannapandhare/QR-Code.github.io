# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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

### Screenshot

![Screenshot](image.png) - Screenshot of Project.

### Links

- Live Site URL: [Live Server Url](https://prasannapandhare.github.io/QR-Code.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I have learned how to make simple templates using HTML and CSS with help of flex properties .

Observe below code for given project.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- displays site properly based on user's device -->

    <link rel="icon" type="image/png" sizes="32x32" href="./Images/favicon-32x32.png">

    <title>Frontend Mentor | QR code component</title>

    <link rel="stylesheet" href="style.css">

</head>

<body>

    <div id="wrapper">
        <div class="container">
            <div class="card">
                <img src="Images/image-qr-code.png" alt="">
                <p class="head">
                    <b>
                        Improve your front-end skills by building projects
                    </b>
                </p>
                <p class="last">
                    Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
                </p>
            </div>
        </div>
    </div>
    </div>

    <div class="attribution">
        Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
        Coded by <a href="#">Prasanna Pandhare</a>.
    </div>
</body>

</html>
```
```css
@import url(https://fonts.google.com/specimen/Outfit);

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Outfit", sans-serif;
    font-weight: 400, 700;
}

#wrapper {
    font-family: "Outfit", sans-serif;
}

.container {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: hsl(220, 15%, 89%);
}

.card {
    width: 20%;
    background-color: hsl(0, 0%, 100%);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    border-radius: 15px;
}

img {
    padding-top: 15px;
    padding-bottom: 20px;
    width: 90%;
    border: 2px, solid, black;
    border-radius: 40px;
}

.head {
    text-align: center;
    font-style: bold;
    font-size: 20px;
    font-weight: 700;
    color: hsl(218, 44%, 22%);
    padding-right: 20px;
    padding-left: 20px;
}

.last {
    text-align: center;
    font-size: 15px;
    color: hsl(212, 15%, 55%);
    padding-top: 20px;
    padding-left: 50px;
    padding-right: 50px;
    padding-bottom: 40px;
}

.attribution {
    font-size: 11px;
    text-align: center;
}

.attribution a {
    color: hsl(228, 45%, 44%);
    text-decoration: none;
}

@media screen and (width<=526px) {
    .container {
        flex-direction: column;
        min-width: 375px;
        padding-left: 15px;
        padding-right: 15px;
        padding-top: 100px;
        padding-bottom: 100px;
    }

    .card {
        width: auto;
    }

    .attribution {
        /* font-size: 11px; */
        text-align: center;
    }
}

@media screen and (width<=375px) {
    /* #wrapper {
        height: 100vh;
    } */

    .container {
        border-radius: 0;
        height: 100%;
        padding-left: 15px;
        padding-right: 15px;
        padding-top: 100px;
        padding-bottom: 100px;
    }

    .card {
        border-radius: 15px;
    }

    .attribution {
        /* font-size: 11px; */
        text-align: center;
    }

}
```

### Continued development

I am trying to improve my skills in media queries.

### Useful resources

- [MDN Docs](https://developer.mozilla.org/en-US/) - Helped me in various learnings. 

## Author

- Website - [Prasanna Pandhare](https://www.your-site.com)
- Frontend Mentor - [@Prasannapandhare](https://www.frontendmentor.io/profile/Prasannapandhare)

## Acknowledgments

I understood the importance of CSS in designing HTML structure.
As well as understood about responsive websites.
