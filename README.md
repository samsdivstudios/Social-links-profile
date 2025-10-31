# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/desktop_version.png)
![](./assets/images/mobile_version.png)

- Solution URL: [https://github.com/samsdivstudios/Social-links-profile](https://github.com/samsdivstudios/Social-links-profile)
- Live Site URL: [https://samsdivstudios.github.io/Social-links-profile/](https://samsdivstudios.github.io/Social-links-profile/)

## My process

### Built with

- Semantic HTML
- CSS
- Flexbox
- Mobile-first workflow

### What I learned

- I've learned to use semantic's as first priority, not just div's.
- I also learned a little Media Queries not sure if I used it properly but I will keep learning.

```html
 <nav>    
  <a href="#">GitHub</a>
  <a href="#">Frontend Mentor</a>
  <a href="#">LinkedIn</a>
  <a href="#">Twitter</a>
  <a href="#">Instagram</a>
 </nav>
```
```css
nav {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 10px;
    list-style-type: none;
}


nav a {
    width: 90%;
    text-decoration: none;
    padding: 14px;
    cursor: pointer;
    font-weight: var(--600-);
    color: var(--white-);
    border-radius: 0.6rem;
    background-color: var(--list-bg-color-);
}
```
### Continued development

I want to continue focusing on:
- Media Queries
- clean HTML and CSS
- CSS Pseudo

## Author
- Frontend Mentor - [@samsdivstudios](https://www.frontendmentor.io/profile/samsdivstudios)
- Twitter - [@samdivstudiods](https://x.com/samdivstudio)
