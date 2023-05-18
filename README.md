# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![Solution Preview](.dist/img/screenshot.jpg)

### Links

- Solution URL: [https://github.com/CareKajzeX/QR-code-component](https://github.com/CareKajzeX/QR-code-component)
- Live Site URL: [https://carekajzex.github.io/QR-code-component/](https://carekajzex.github.io/QR-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [Sass](https://sass-lang.com/) - CSS Preprocessor
- Variables
- Nesting
- Partials

### What I learned

I learned how to center div horizontally and vertically at the same time using two Flexboxes.

Below is the code for using the flexbox:

```scss
.qr-code-component {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;

  .qr-code {
    background: $white-color;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    text-align: center;
    width: 20rem;
    height: 31.1rem;
    border-radius: 1rem;

    &-image {
      width: 18rem;
      margin: 1rem 0;
    }

    &-content {
      padding: 0 1rem;
    }
  }
}
```

I also learned about Markdown language by writing this document which happens to be the first.

### Continued development

For the next project I would like to use Grid to do center div to the middle of the screen and compare the solutions with Flexbox.

### Useful resources

- [Traversy Media](https://www.youtube.com/@TraversyMedia) - Place where I learn everything.
- [Flexbox Crash Course](https://www.youtube.com/watch?v=3YW65K6LcIA) - Great resource to go trough to help with completing this challenge.

## Author

- Github - [CareKajzeX](https://github.com/CareKajzeX/)
- Frontend Mentor - [@CareKajzeX](https://www.frontendmentor.io/profile/CareKajzeX)
- Twitter - [@CareKajze](https://twitter.com/CareKajze)