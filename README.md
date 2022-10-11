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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![Screenshot 2022-10-11 at 9 09 39 PM](https://user-images.githubusercontent.com/38833326/195137774-aad0af79-f4bc-42a0-bf4d-ce86864ef1b8.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/hashmi7917/Frontend-Menoter-QR-Challenge-Completed.git)
- Live Site URL: [Add live site URL here](https://hashmi7917.github.io/Frontend-Menoter-QR-Challenge-Completed/)

## My process

- First of all i code whole markup
- And then started styles cascading
- Finally Made it responsive

### Built with

- HTML5 markup
- CSS custom properties
- CSS root variables
- Mobile responsive webiste

### What I learned

Html markup and simple layots with css, custom properties with root variables, managing margin & paddings how to use 'rem' for font size and lastly responsive design with using max-width and vw,vh units for sizes, thanks to frontend mentor.

To see how you can add code snippets, see below:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->
    <link rel="stylesheet" href="style.css" />
    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />

    <title>Frontend Mentor | QR code component</title>
  </head>
  <body>
    <div class="container">
      <div class="qr-box">
        <div class="main">
          <img class="qr-img" src="./images/image-qr-code.png" alt="qr" />
        </div>
        <div class="content">
          <h2>Improve your front-end skills by building projects</h2>
          <p>
            Scan the QR code to visit Frontend Mentor and take your coding
            skills to the next level
          </p>
        </div>
      </div>
      <div class="footer">
        Challenge by
        <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
          >Frontend Mentor</a
        >. Coded by <a href="https://github.com/hashmi7917">Hashmi</a>.
      </div>
    </div>
  </body>
</html>
```

```css
@import url("https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap");

* {
  box-sizing: border-box;
}
/* COLORS */
:root {
  --primary: hsl(212, 45%, 89%);
  --qr-box: hsl(0, 0%, 100%);
  --qr-bg: hsl(218, 44%, 22%);
  --content: hsl(220, 15%, 55%);
  --font-outfit: "Outfit", sans-serif;
}

html {
  /* to easily calculate rem values */
  font-size: 10px;
}

body {
  margin: 0;
  padding: 0;
}

.container {
  width: 100vw;
  height: 100vh;
  padding-top: 15vh;
  background-color: var(--primary);
}

.qr-box {
  background-color: var(--qr-box);
  width: 100%;
  max-width: 320px;
  margin: 0 auto;
  border-radius: 20px;
  padding: 15px;
  box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
}

.qr-img {
  width: 100%;
  border-radius: 16px;
}

.content {
  padding: 0 20px 20px 20px;
  text-align: center;
  font-family: var(--font-outfit);
}

h2 {
  font-size: 2.2rem;
  font-weight: 700;
}

p {
  color: var(--content);
  font-size: 1.6rem;
}

.footer {
  text-align: center;
  padding: 1rem;
}
```

```js

```

### Continued development

I found that i got probles while settings image width, and properly layouting html markup with css, also faced difficulties in setting constant with of elements.

### Useful resources

- [Example resource 1](https://stackoverflow.com/questions/10189356/how-to-add-screenshot-to-readmes-in-github-repository) - This helped me for adding screenshot in github readme. I really liked this website and will use it going forward.

## Author

- Website - [Hashmi](https://hashmi7917.github.io/hashmiportfolio/)
- Frontend Mentor - [@hashmi-twitter](https://twitter.com/@hash_m_ee)
- Twitter - [@hashmi-github](https://github.com/hashmi7917)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.
