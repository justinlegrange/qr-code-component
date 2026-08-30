# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

![The QR code component.](./qr-preview.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Tailwind CSS](https://tailwindcss.com/) - CSS preset library
- [Neovim](https://neovim.io/) - Code editor

### What I learned

There's not too much to this component that's new for me, outside of using Figma designs to create the components. A small thing I *did* learn - this was the first project in which I used Tailwind outside of a framework environment like Astro. I also did end up learning about using `flex` + `h-screen` in the parent and `m-auto` on the child element to vertically center the child:

```html
<div class="flex h-screen">
```

And as always, working on this project gave me a great chance to work through more Neovim memorization - Vim actions, setting up the Nvim LSP, and other helpful things.

### Continued development

Although this component is straightforward, I'd like to see how others do it and if there are any ways that are better best practices/ways to refactor and get cleaner code in the source.

I'd also like to learn if there's a better way to get the shadow to appear - my component seems to have it all around, compared to the mockup having it in what looks like a single direction.

### Useful resources

- [Stackoverflow post detailing how to center a div using flexbox vertically](https://stackoverflow.com/questions/55056513/vertical-align-with-tailwind-css-across-full-screen-div) - This was super helpful in getting my div centered. Being able to just apply `h-screen` paired up with `m-auto` is a quick and easy way to get something in the center of the screen easily.

## Author

- Website - [https://jlegrange.dev](https://jlegrange.dev)
- Frontend Mentor - [@justinlegrange](https://www.frontendmentor.io/profile/justinlegrange)
