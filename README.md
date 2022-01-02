# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

- Mobile: [https://github.com/rogeriobautz/stats-preview-component/blob/master/screenshots/mobile.png]
- Desktop: [https://github.com/rogeriobautz/stats-preview-component/blob/master/screenshots/desktop.png]

### Links

- Solution URL: [https://github.com/rogeriobautz/stats-preview-component/]
- Live Site URL: [https://rogeriobautz.github.io/stats-preview-component/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned about CSS blend modes using images and backgrounds, improved my knowledge about grid layouts and media queries.

I had a lot of throubles before get in this code:

```html
<div class="hero-box">
  <img
    class="hero-desktop hero"
    src="./images/image-header-desktop.jpg"
    alt="Women working in an office"
  />
  <img
    class="hero-mobile hero"
    src="./images/image-header-mobile.jpg"
    alt="Women working in an office"
  />
</div>
```

```css
.hero-box {
  display: flex;
  justify-content: center;
  align-items: center;
  grid-area: hero;
  width: 100%;
  height: 100%;
  background-color: hsl(277, 64%, 61%);
}

.hero {
  width: 100%;
  mix-blend-mode: multiply;
}
```

### Continued development

I have to study more about display and positions.

### Useful resources

- I struggled for a hole until youtube suggested this video on one of my searches:
  - Kevin Powell [How to use mix-blend-mode, and how to avoid problems with it](https://youtu.be/TAA89nkEuhw)
  - The first 3 minutes of the video solved my problem.

## Author

- [Rogério Bautz](https://github.com/rogeriobautz)
- Frontend Mentor - [@rogeriobautz](https://www.frontendmentor.io/profile/rogeriobautz)
- Instagram - [@rogerio.bautz](https://www.instagram.com/rogerio.bautz)
