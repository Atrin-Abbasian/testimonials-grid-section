# Testimonials grid section

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](design/testimonials.png)

### Links

- GitHub URL: [GitHub Repository](https://your-solution-url.com)
- Live Site URL: [GitHub Pages](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS3 custom properties
- Bootstrap 4
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This project, despite being simple and small, taught me good and small points. Tips that will help me a lot in the future. It was a good experience overall.

```html
    <div class="section-5-info d-flex">
        <img src="images/image-kira.jpg" alt="kira" class="img-fluid rounded-circle">
        <div class="d-flex flex-column">
            <span class="kira-name">Kira Whittle</span>
            <span class="kira-verified">Verified Graduate</span>
        </div>
   </div>
```
```css
  @media screen and (min-width: 992px) {
    .main-section {
        height: 720px;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .grid-section {
        display: grid;
        grid-template-columns: 23% 23% 23% 23%;
        grid-template-rows: 282px 266px;
        grid-template-areas: "a a b e" "c d d e";
        gap: 1.5rem;
    }
    .section-1 {
        grid-area: a;
    }
    .section-2 {
        grid-area: b;
    }
    .section-3 {
        grid-area: c;
    }
    .section-4 {
        grid-area: d;
    }
    .section-5 {
        grid-area: e;
    }
```

## Author

- Website - [My Website](https://www.atrindev.ir)
- Linkedin - [My Linkedin](https://www.linkedin.com/in/atrindev)