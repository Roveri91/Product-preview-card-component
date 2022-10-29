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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/Roveri91/Product-preview-card-component.git)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- @media query for switch from desktop to smartphone viewer
- @import for import font-family from googlefont


### What I learned

Making this card prototype i`ve achieved:

1) a better usage of the @media query property of CSS 

   ```CSS
  ```@media only screen and (max-width: 550px)
  ```

2) a better usage of the flexbox, margin property for center and place elements inside a div element

```HTML
```<div class="prices">
        <h2>$149.99</h2>
        <h4>$169.99</h4>
    </div>
```

```CSS
```.prices {
  display: flex;
  gap: 1rem;
  align-items: center;
  margin-bottom: 1.75rem;
}
```

3) the knowledge of the function @import in order to import different fonts from a different website

```CSS
```@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&display=swap');
```


### Continued development

I would like to keep focusing on flexbox, margin and padding property because untill now is a topic where i don`t fel
confortable and sure at the 100%.



### Useful resources

- [resource](https://www.youtube.com/watch?v=TkdBtmwWyZo) - This youtube video helps me a lot with the margin, flexbox and white spacing.
I believe Kevin Powell is the god of the CSS ;)


## Author

- Github - [Roveri91](https://github.com/Roveri91)
- Frontend Mentor - [@Roveri91](https://www.frontendmentor.io/profile/Roveri91)


