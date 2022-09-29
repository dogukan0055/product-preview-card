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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop Design](/screenshots/desktop.png)
![Mobile Design](/screenshots/mobile.png)
![iPhone12 Design](/screenshots/iPhone12.png)

### Links

- Solution URL: [Link to the solution](https://github.com/dogukan0055/product-preview-card)
- Live Site URL: [Link to the live site](https://dogukan0055.github.io/product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive design

### What I learned

```html
<header>
  <h1>Gabrielle Essence Eau De Parfum</h1>
  <h2>PERFUME</h2>
</header>
```

```css
@media (hover: hover) {
  button:hover {
    background-color: rgb(1, 73, 73);
  }
}

@media screen and (max-width: 420px) {
  .container {
    height: auto;
  }

  .card {
    flex-direction: column;
    width: 340px;
    height: 600px;
    padding-right: 0;
  }

  .desktop {
    display: none;
  }

  .mobile {
    display: block;
    width: 100%;
    height: 250px;
  }

  .card-inline {
    width: 100%;
    padding: 30px;
  }

  h2 {
    font-size: small;
    letter-spacing: 4px;
    font-weight: 500;
    margin-block-end: 1rem;
    margin-block-start: 0;
  }

  h1 {
    max-width: 400px;
  }

  p {
    max-width: 264px;
  }

  button {
    width: 100%;
  }
}
```

### Continued development

I'm still not very comfortable with mobile designs and I definitely need to improve my coding skills in some ways. Gotta get used to media queries.

### Useful resources

- [Youtube](https://www.youtube.com/watch?v=aoB6cloAB1E&ab_channel=LearnSomething) - I've watched it to get some tips and how to plan layout and stuff. Every one has it's own methods, but this guy helped me a lot so I have to give his credits.

## Author

- Website - [Doğukan ŞIHMAN](https://dogukansportfolio.w3spaces.com/)
- Frontend Mentor - [@dogukan0055](https://www.frontendmentor.io/profile/dogukan0055)
- Twitter - [@bedavatekme](https://www.twitter.com/bedavatekme)

## Acknowledgments

Like I said above, YouTube and of course FrontEndMentor helped a lot during this journey. But it's not just about watching and learning, you need to practice these skills. So just try to code, try to think, try to write something. That's all I can say I guess.
