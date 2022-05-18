# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Bootstrap ](https://getbootstrap.com/) - responsive design


### What I learned

I learnt how to add an overlay to the image and i was super happy. It was challenge to get the overlay to work. I also learnt how to use the hover states for the interactive elements.



```html
<div class="card-image-section">
              <img src="/images/image-equilibrium.jpg" class="card-img-top img-responsive px-2 pt-4" alt="...">
            <div class="overlay">
              <a href="#" class="icon" title="User Profile">
                <img src="/images/icon-view.svg" alt="User Profile">
              </a>
            </div>
            </div>
```
```css
.overlay {
  position: absolute;
  top: 9%;
  bottom: 0;
  left: 3%;
  right: 0;
  height: 91%;
  width: 96%;
  opacity: 0;
  transition: .3s ease;
  background-color: hsla(178, 100%, 50%, 0.603);
  border-radius: .5em;
}
```



### Continued development

I will continue to develop and take up more challenge. 

### Useful resources

- [W3schools](https://www.w3schools.com) - This helped me for the challenge (the overlay on hover).



## Author

- Frontend Mentor - [@muubaraq](https://www.frontendmentor.io/profile/muubaraq)
- Twitter - [@muubaraq](https://www.twitter.com/muubaraq)

