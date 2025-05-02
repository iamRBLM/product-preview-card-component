# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Project Preview](/images/project-preview.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- CSS Flexbox

### What I learned

I continue to apply the technique of writing clean HTML and CSS code, using CSS utilities classes and CSS Variables (custom properties), for different styles, such as:

```html
<h2 class="text-lg text-black my-md"></h2>
```

```css
.text-lg {
  font-size: 2.28rem;
  line-height: 100%;
  font-family: "Fraunces", serif;
}

:root {
  --Black: hsl(212, 21%, 14%);
}

.text-black {
  color: var(--Black);
}

.my-md {
  margin: 24px 0;
}
/*
Naming convention:
[m] sets margin on the Y-axis (top and bottom).
[md] indicates medium size.
*/
```

Another example from the code:

```html
<section class="card-content bg-white p-lg"></section>
```

```css
:root {
  --White: hsl(0, 0%, 100%);
}

.bg-white {
  background-color: var(--White);
}

.p-lg {
  padding: 32px;
}
/*
Naming convention:
[p] sets equal padding on all sides.
[md] refers to the medium size.
*/
```

In this way the CSS elements are not fill with bunch of different CSS properties, and it puts everything in logical order.

I will keep developing this way of writing HTML and CSS - it also make it easy to read the code.

### Continued development

I will keep improving my HTML and CSS skills and learning new tricks and techniques. I will be focusing specifically on mastering CSS Flexbox and Grid techniques and responsive web design.

## Author

- Frontend Mentor - [@rosenblumitamar](https://www.frontendmentor.io/profile/rosenblumitamar)
- Twitter - [@rosenblumitamar](https://x.com/ItamarRosenblum)
