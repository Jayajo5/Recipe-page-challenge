# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Recipe page

### Screenshot

![Screenshot of my Recipe page](assets/images/Screenshot%202025-04-05%20at%2013-02-03%20Frontend%20Mentor%20Recipe%20page.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- Different screen sizes Mobile:380px and Desktop:1440px

```css
@media screen and (max-width:380px) {
    .recipe-section h1{
        margin-top: 8px;
        font-size: 17px;
    }
    
    .recipe-section p{
        margin-top: 13px;
        font-size: 12px;
    }

    .all-content{
        padding: 5px 8px;
    }

/*----------------------------Preparation Section----------------------*/
.preparation-section{
    padding: 12px;
    margin-top: 17px;
}

.preparation-section p{
    font-size: 13px;
    font-weight: 600;
}

.list-items-one{
    font-size: 13px;
    line-height: 22px;
}

.list-items-one li::before{
    font-size: 24px;
    margin-right: 9px;
}

.list-items-two{
    font-size: 13px;
    line-height: 15px;
}

/*----------------------------Ingredients Section----------------------*/
.ingredients-section{
    margin-top: 17px;
}

.list-items-two{
    font-size: 13px;
    line-height: 17px;
}

.list-items-two li::before{
    font-size: 24px;
    margin-right: 9px;
}

hr{
    margin: 5px 0;
}

/*----------------------------Instructions Section----------------------*/
.list-items-three{
    line-height: 22px;
    padding: 4px;
    margin: 2px;
}

/*----------------------------Nutrition Section----------------------*/
.nutrition h2{
    margin-top: 17px;
}

.nutrition p{
    margin-top: 13px;
    font-size: 13px;
}

.nutrition-table{
    margin-top: 8px;
}

.hr{
    margin: 1px 0;
}

.nutrition-table div{
    width: 38%;
    padding: 5px;
}

h2{
    font-size: 15px;
}
}
```
### Continued development

- In future projects will learn more CSS properties.

### Useful resources

- [CSS Tricks](https://css-tricks.com/centering-css-complete-guide/) - This helped me for Centering in CSS. I really liked this pattern and will use it going forward.
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Glossary/Flexbox) - This is an amazing free resource which helped me finally understand Flexbox. I'd recommend it to anyone still learning this concept.

## Author

- GitHub - [@Jayajo5](https://github.com/Jayajo5)
- Frontend Mentor - [@Jayajo5](https://www.frontendmentor.io/profile/Jayajo5)

## Acknowledgments

A big thanks to the Frontend Mentor community for feedback and inspiration! 🚀
