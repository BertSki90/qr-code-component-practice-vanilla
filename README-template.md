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
- [Acknowledgments](#acknowledgments)

## Overview

I built a QR component with basic HTML and JavaScript.

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://bertski90.github.io/qr-code-component-practice-vanilla/)
- Live Site URL: [Add live site URL here](https://bertski90.github.io/qr-code-component-practice-vanilla/)

## My process

HTML

1. Set up a structure for a card to put all information inside.

2. Inside the card starting from the top insert image, heading, and paragraph.

CSS

3. In this order style the card, image, heading, and paragraph.

4. To be able to see the changes during the styling of the card I changed to background color first. This way I can see the card. Another way would have been to put a border around the card.

5. Needed to center the card on the screen horizontlly and vertically.

6. Apply styling to main, img, h1, and p. I played with the units until the spacing looked like the design.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I needed to research on how to center the card horizontally and vertically on the screen. Below is the code that I used for centering.

```
body {
    background-color: var(--light-gray);
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

/* ---CARD--- */

main {
    display: flex;
    width: 370px;
    flex-direction: column;
    background-color: var(--white);
    margin: auto;
    border-radius: 20px;
    text-align: center;
    padding: 25px;
}
```

I read that when rounding corners of an element inside another element with rounded corners to make it look more uniform half the border radius for the inside element.

In the CSS setting up and calling on root values as well as importing fonts.

### Continued development

I am a newbie. I want to continue to improve my code. This project taught me to focus on mobile first design and centering elements.

### Useful resources

- [freeCodeCamp](https://www.freecodecamp.org/news/css-vertical-align-how-to-center-a-div-text-or-an-image-example-code/) - This helped me with centering elements. I really liked this pattern and will use it going forward.
- [W3Schools](https://www.w3schools.com/css/css_align.asp) - This is an amazing article which helped me with centering elements. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Albert Ski](https://bertski90.github.io/qr-code-component-practice-vanilla/)
- Frontend Mentor - [@BertSki90](https://www.frontendmentor.io/profile/BertSki90)
- Twitter - [@BertSki90](https://twitter.com/BertSki90)

## Acknowledgments

Thank you to freeCodeCamp. It has introduced me to the coding world.
