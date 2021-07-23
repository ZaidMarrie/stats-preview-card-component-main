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

#### Desktop view

![Desktop View](https://user-images.githubusercontent.com/84665360/126758376-f198d6db-46db-4865-ad55-60862dd3be59.png)

#### Mobile view

![Mobile View](https://user-images.githubusercontent.com/84665360/126758400-d1e9bce0-38ad-4621-8e0c-772b69af5ce3.png)

### Links

- Solution URL: [My Solution](https://your-solution-url.com)
- Live Site URL: [Live Site](https://zaidmarrie.github.io/stats-preview-card-component-main/)

## My process

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

What I've learned in this challenge was that images behave in a very weird manner when a device screen is adjusted. The image is a child element of a flex-item and it does not take up the full height of the container as the height adjusts according to the width specified to keep it's aspect ratio, meaning the image is not stretched. I also learn that an image creates a space underneath to which is for when images are added inline with text. It accomodates for letters like y, g, j .etc which has sections that moves below a text baseline. This can be fixed by setting it's display property to block.

I added some code snippets, see below:

```css
img{
    width: 100%;
    display: block;
}
```
```css
.image-wrapper,
.main-container{
    width: 100%;
    flex: 1 1 50%;
}
}
```

### Continued development

I will continue exploring and experimenting with images to get them to behave in a way which I desire to help me gain more control over images and their behavior.

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@ZaidMarrie](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

I would like to thank Kevin Powell yet again for the useful content he creates it is very helpful when you are learning web development. Thanks for being so kind to make an effort to create valuable content that are helpful to others.
