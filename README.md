## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

![Recipe page](<./Screenshot%20(2).png>)

### Links

- Solution URL: [Recipe Page](https://github.com/alimassidik210/Recipe-page.git)
- Live Site URL: [Recipe Page](https://recipe-page-ten-neon.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this project, I learned how to use CSS pseudo-elements and media queries.

To see how you can add code snippets, see below:

```css
:root {
  --bgcolor-rose-white: hsl(330, 100%, 98%);
  --color-nutmeg: hsl(14, 45%, 36%);
  --color-dark-raspberry: hsl(332, 51%, 32%);
  --color-white: hsl(0, 0%, 100%);
  --color-eggshell: hsl(30, 54%, 90%);
  --color-light-grey: hsl(30, 18%, 87%);
  --color-wenge-brown: hsl(30, 10%, 34%);
  --color-dark-charcoal: hsl(24, 5%, 18%);
}
```

```css
.nutrition-container table td:first-child,
table td:last-child {
  width: 50%;
}

.nutrition-container table td:first-child {
  padding-left: 2rem;
}

.nutrition-container table td:last-child {
  font-weight: bold;
  color: var(--color-nutmeg);
}

@media only screen and (min-width: 601px) {
  body {
    padding: 4rem;
  }

  .container .hero-img {
    padding: 2rem 2rem 0 2rem;
  }

  .container .hero-img img {
    border-radius: 0.5rem;
  }
}
```

### Continued development

"In the next project, I want to use SASS to make writing CSS code simpler."

### Useful resources

- [chatgpt](https://www.example.com) - This helped me for many reason. I really liked this AI and will use it going forward.

## Author

- Website - [alim assidik](https://mini-portfolio-yp8m.onrender.com)
- Frontend Mentor - [@alimassidik210](https://www.frontendmentor.io/profile/alimassidik210)
- Instagram - [@alim.assiik210](https://www.instagram.com/alim.assidik210)
