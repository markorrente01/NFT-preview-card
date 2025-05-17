![preview](/images/preview.jpg)
# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover states for interactive elements

### Screenshot

![desktop](/images/nft-preview-card-sc-desktop.png)
![ipad](/images/nft-preview-card-sc-iospad.png)
![IOS-11](/images/nft-preview-card-ios11.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- SCSS


### What I learned

I learnt how to make this special hover effect on the nft image.

```html
<section>
  <div class="image_wrapper"><img src="images/image-equilibrium.jpg" alt="NFT preview"></div>
  <div class="middle"><img src="images/icon-view.svg" alt="view"></div>
</section>
```

```scss
main section:nth-child(1){
    position: relative;
    margin-bottom: 1.563rem;
}

main section:nth-child(1):hover img{
    display: block;
    cursor: pointer;
}

main section:nth-child(1):hover .middle{
    background-color: hsla(178, 100%, 50%, 0.5);
    cursor: pointer;
}

.middle{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    height: 100%;
    width: 100%;
    display: grid;
    place-content: center;
    border-radius: 9px;
    transition: 0.3s linear;

    img{
        display: none;
    }
}
```


### Continued development

I will continue taking more frontend mentor projects.

### Useful resources

- [chatgpt](https://chatgpt.com/) - This is a great help when you get stuck in a project but you must give it a good prompt for better result.
- [W3schools](https://www.w3schools.com/) - This is an amazing free school to learn different programming languages from beginner to pro level.

## Author

- Frontend Mentor - [@Markorrente](https://www.frontendmentor.io/profile/markorrente01)