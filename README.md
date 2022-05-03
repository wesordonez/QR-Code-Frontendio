# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

This is my first Frontend.io project using CSS/HTML. The challenge was to recreate a QR Code component off of reference images. 

### Screenshot

![](images/screenshot.png)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap


### What I learned

Despite being a simple project, I learned a lot given this is my first solo project. I took things my own way and I tried to use a top-down approach using everything I have learned so far in a web-developement bootcamp. 

I used HTML to create the layout of the QR component. I learned about Bootstrap cards after beginning the process which may have been an easier way to approach this project. Despite using a "card" class, I didn't use the bootstrap cards and built everything off raw CSS and HTML.I did use a "row" class in bootstrap to help with sizing and making the component reactive. 

To see how you can add code snippets, see below:

```html
  <div class="row">

    <div class="card col-lg-4">
      <div class="col-lg-4">
        <img src="images/image-qr-code.png" alt="qr-code">
      </div>
      <div class="col-lg-4">
        <h1>Improve your front-end skills by building projects</h1>
      </div>
      <div class="col-lg-4">
        <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
      </div>

    </div>
  </div>
```
```css
.card {
  background-color: #fff;
  width: 300px;
  margin: 10% auto;
  border-radius: 15px;
  padding-top: 15px;
  padding-bottom: 15px;

}
```


### Continued development

I struggled using percentages to define the width of the card. I wasn't able to get it to work in a smooth fashion through the different sizes. I ended up hardcoding a width to 300px as shown above in the CSS code snippit. This gave the desired look through out display resizing. I don't know if this is a good/normal practice in HTML/CSS but in most other languages hardcoding values is usually not best practice.


## Author

- Website - [Wesley Ordonez](https://wesordonez.github.io/cv/)
- Frontend Mentor - [@wesordonez](https://www.frontendmentor.io/profile/wesordonez)


