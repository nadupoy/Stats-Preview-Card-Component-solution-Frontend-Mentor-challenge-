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



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Desktop - 1440px](https://raw.githubusercontent.com/nadupoy/Stats-Preview-Card-Component-solution-Frontend-Mentor-challenge-/main/design/Desktop%20-%201440px.png)

![Tablet - 768px](https://raw.githubusercontent.com/nadupoy/Stats-Preview-Card-Component-solution-Frontend-Mentor-challenge-/main/design/Tablet%20-%20768px.png)

![Mobile - 375px](https://raw.githubusercontent.com/nadupoy/Stats-Preview-Card-Component-solution-Frontend-Mentor-challenge-/main/design/Mobile%20-%20375px.png)


### Links

- Solution URL: [https://www.frontendmentor.io/solutions/stats-preview-card-component-solution-using-html5-and-css3-mwjSmp208](https://your-solution-url.com)
- Live Site URL: [https://stats-preview-card-component-solution-nadupoy.netlify.app/](https://your-live-site-url.com)

## My process

### Built with

- Visual Studio Code
- HTML5 markup
- CSS3
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The <picture> tag in HTML, what it does and where it is applicable.

```html
 <picture>
    <source media="(min-width: 992px)" srcset="images\image-header-desktop.jpg">
    <source media="(min-width: 601px)" srcset="images\image-header-mobile.jpg">
    <source media="(min-width: 320px)" srcset="images\image-header-mobile.jpg">
    <img src="images/favicon-32x32.png">
</picture>
```

Positioning elements using CSS Grid.
```css
#grid-container{
    width: 270px;
    margin: auto;
    display: grid;
    grid-template-rows: auto auto auto;
    text-align: center;
    }
```




### Continued development

- I would like to better understand CSS Grid, especially with regards to responsive design in positioning elements.

### Useful resources

- [W3 Schools](https://www.w3schools.com/css/css_grid.asp) - This website helped me understand CSS Grid. I really liked this website and will use it going forward.




## Author


- Frontend Mentor - [@nadupoy](https://www.frontendmentor.io/profile/nadupoy)
- LinkedIn - [Grace Sampao](https://www.linkedin.com/in/grace-sampao-49a3129b/)




