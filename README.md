# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout for the site depending on their device's screen size

### Screenshot

-   Desktop Screenshot
    ![Desktop Solution](<./Solution-Screenshort(Desktop).png>)

-   Mobile Screenshot
    ![Mobile Solution](<./Solution-Screenshort(Mobile).png)

### Links

 Frontend Mentor Solution URL: [Frontend Mentor Solution Page](https://www.frontendmentor.io/solutions/fourcardfeaturesectionmaster-solution-uD-Oht_upH)
- Live Site URL: [Live Hosted Website](https://mharvel13.github.io/Four-Card-Feature-Section-Master/)
- Github Solution URL: [Github Hosted Codes](https://github.com/Mharvel13/Four-Card-Feature-Section-Master)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow

### What I learned

#### Grid Layout System

This challenge was useful to help in practicing the grid system and understanding how to create complex layout.
Using the grid syntax , the four card column layout was created as seen in the snippet below

```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2, 1fr);
    justify-items: center;
    align-items: center;
    gap: 10px;
}
```

To specify the number of columns each section/card takes up, it was specified individually using the ` grid-row` property

```css
.box:nth-child(1) {
    grid-row: 1 / 3;

    /* more codes... */
}
```

### Useful resources

-   [W3Schools Grid Reference](https://www.w3schools.com/css/css_grid.asp)

## Author

-   GitHub Profile - [Mharvel13](https://github.com/Mharvel13)
-   Frontend Mentor - [Marvel Victor](https://www.frontendmentor.io/profile/Mharvel13)
-   Twitter - [Marvel](https://twitter.com/Mharvel_O)
