# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/screenshot/Blog%20preview%20card.png)
![](./assets/screenshot/Blog%20preview%20card%20-%20mobile.png)

### Links

- Solution URL: [GitHub](https://github.com/Rahulg8270/Blog-preview-card)
- Live Site URL: [Vercel](blog-preview-card-mocha-five.vercel.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media queries

### What I learned

During this challenge, I learned how structuring the HTML content properly first makes the css part a bit easier.

I used semantic elements and class names for html elements, also used accessiblity attributes like role and aria-label.

below is my code snippet for html that I'm proud of:

```html
<main
      class="preview-card"
      role="main"
      aria-label="Article preview about HTML and CSS foundations"
    >
      <img
        src="./assets/images/illustration-article.svg"
        class="preview-illustration"
        alt="Abstract illustration containing code and curly braces"
      />
      <section aria-label="Category and publish Info">
        <span class="preview-category">Learning</span>
        <p class="preview-time">
          Published on <time datatime="2025-07-26">26th July 2025</time>
        </p>
      </section>

      <h1 class="preview-title">HTML & CSS Foundations</h1>
      <p class="preview-description">
        These languages are the backbone of every website, defining structure,
        content and presentation.
      </p>
      <figure class="profile-figure">
        <img
          src="./assets/images/image-avatar.webp"
          alt="Portrait of Greg Hooper"
        />
        <figcaption class="profile-name">Greg Hooper</figcaption>
      </figure>
    </main>
```

### Continued development

I Like to explore more about typography and how to make it resposive regardless of the device dimensions.


## Author

- Website - [Portfolio](https://www.crio.do/learn/portfolio/rahul-g8270/?edit=true)
- Frontend Mentor - [/Rahulg8270](https://www.frontendmentor.io/profile/Rahulg8270)
- LinkedIn - [/rahulganta](https://www.linkedin.com/in/rahulganta/)


## Acknowledgments

Thanks [Frontend Mentor](https://www.frontendmentor.io/) for the challenge instructions and design files, but most important community.


