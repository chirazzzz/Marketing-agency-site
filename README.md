# Jake&Elwood Marketing Agency Site

[Link to live deploy](https://chirazzzz.github.io/Marketing-agency-site/)

This is a multi-page Marketing Agency website which I created while following a tutorial from [Kevin Powell](https://www.kevinpowell.co/) on [Scrimba](https://scrimba.com/). I have recently graduated from the [School of Code](https://www.schoolofcode.co.uk/) however this site was created in 2020. I converted all the CSS to SCSS because I wanted to split up the CSS into more readable, manageable files. I used Variables, Mixins and Partials to achieve this.

## Table of contents

- [Running Locally](#running-locally)
- [Description](#description)
- [Challenges](#challenges)
- [Overview](#overview)
  - [My Goals](#my-goals)
  - [Screenshot](#screenshot)
- [My Process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Running Locally

Since this site is made with HTML, CSS and JavaScript it doesn't require any setup or installing NPM modules. Simply clone or fork the repo onto your local machine and open the index.html file using your web browser. It looks great in Chrome, Firefox and Safari!

## Description

This Marketing Agency site is a showcase project for potential clients. It's totally responsive and has a clean, clear, uniform style throughout. I converted all the CSS to SCSS because I wanted to split up the CSS into more readable, manageable files. I used Variables, Mixins and Partials to achieve this.

This was the first multi-page site I'd created so I had to think carefully about my design choices. On mobile screens the menu is only accessible by clicking the hamburger, so it was crucial to add aria-labels for screen reader users. I had never considered accessibility before this project so adding the 'Open navigation' and 'Close navigation' labels was a real eye opener.

## Challenges

- The biggest issue was styling the large hero image on the home page. This took lots of trial and error but I'm satisfied with how it looks.
- Creating a full screen menu which has offset positioning and slides over the page smoothly but only at mobile screens
- Learning how to use pseudo classes like ::after to add styled content to the page without adding to HTML

## Overview

### My goals

Users should be able to:

- Access the menu on mobile screens by clicking the hamburger menu
- View the optimal layout for each of the website's pages depending on their device's screen size
- View each page and be able to toggle between the tabs to see new information

### Screenshot

![Screenshot of portfolio site](img/Jake%20and%20Elwood.png)

## My process

### Built with

- Semantic HTML5 markup
- SCSS Variables, Mixins and Partials
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The main thing I learned by building my this site was how to create a hamburger menu which toggles a menu overlay on mobile screens. It was important to have this disabled on tablet and desktop screens to give users a traditional desktop nav menu. I believe giving users what they expect contributes to better UX.

I also learned the difference small styling details like using negative margins and pseudo classes can make. For example the code below creates the thick yellow band which highlights the about us and contact page titles. 

```css
.page {
  &-title::after {
    content: "";
    display: block;
    width: 100%;
    border-bottom: 25px solid $color-border;
    margin-top: -40px;
    margin-left: 10px
  }
}
```

## Author

- LinkedIn - [@chiragmehtauk](https://www.linkedin.com/in/chiragmehtauk/)
- Twitter - [@chirag_uk](https://twitter.com/chirag_uk)