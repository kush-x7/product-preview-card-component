\*\*# Frontend Mentor - Product preview card component solution

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS

### What I learned

**1. Learned how to show different images using css**

```html
<div class="card__image">
  <img
    src="./images/image-product-desktop.jpg"
    alt="card_image"
    class="desktopImage"
  />
  <img
    src="./images/image-product-mobile.jpg"
    alt="card_image"
    class="mobileImage"
  />
</div>
```

```css
.mobileImage {
  display: none;
}

@media screen and (min-width: 600px) {
  .mobileImage {
    display: block;
  }
  .desktopImage {
    display: none;
  }
}
```

**2. Leaned animation using Css**

### Useful resources

- [Box Shadow Generator](https://getcssscan.com/css-box-shadow-examples) - This helped me with the box shadows.
- [Animation](https://animista.net/play/text/tracking-in/tracking-in-expand) - This is an amazing site for css animation.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**
