# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Author](#author)


## Overview
  -3 column preview card  
### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Screenshot_of_webPage](./images/ScreenShot_of_webPage.jpg)

Added a screenshot of my solution.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
### What I learned

Use this section of css helped me to make it responsive learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

```css
/*At Start*/
.container{
    height:100vh;
    background:var(--Very_light_gray);
    display:flex;
    justify-content: center;
    align-items:center;
}
/*for tabs and device within 800px*/
@media screen and (max-device-width:800px) {
    body{
        overflow: auto;
    }
    .container{
        height:100%;
        margin:20px;
        display: grid;
        grid-template-columns: 300px 300px;
    }
}
/*for mobile and device within 480px*/
@media screen and (max-device-width:480px) {
    body{
        overflow: auto;
    }
    .container{
        height:100%;
        margin:20px;
        display: flex;
        flex-direction: column;
    }
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.


## Author

- Frontend Mentor - [@JakeCodes42](https://www.frontendmentor.io/profile/JakeCodes42)
