# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Recipe page solution](#frontend-mentor---recipe-page-solution)
  - [Table of contents](#table-of-contents)
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

- Solution URL: [Solution](https://github.com/Stephen-Salano/recipe-page-main)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned
Using media queries to style different screen sizes versions

```css
@media (min-width: 400px) and (max-width: 1440px){
    #container{
        display: flex;
        flex-direction: column;
        border-radius: 15px;
        /* Ensure the container size never grows past this size */
        max-width: 45rem;
        margin: 2rem;
        padding: 2rem;
    }
    header > img{
        border-radius: 10px;
        height: auto;
        /* image will not exceed the width of it's container */
        max-width: 100%;
        /*Maintains aspect ratio */
        min-width: 0px;
        flex-grow: 1;
        flex-shrink: 1;
    }
@media(max-width: 375px ){
    #container{
        max-width: 100%;
    }
}
```
## Author

- Website - [Stephen Salano](https://www.your-site.com)
- Frontend Mentor - [Stephen-Salano](https://www.frontendmentor.io/profile/yourusername)
