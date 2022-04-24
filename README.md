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
This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

### Screenshot

![](/images/Screenshot%20(14).png)


### Links

- Solution URL: (https://www.frontendmentor.io/solutions/qrcode-solution-built-with-css-flex-SkucImfS5)
- Live Site URL: (https://frontend-mentor-qr-code-solution.netlify.app/)

## My process
I started out with structuring my html, after whichh I got to styling.
I made a mistake in my styling, I gave a div a class name of "body" and was styling the body element in my style instead of the class. I figured something was wrong when my work was not responsive in mobile view and had to retrace my steps
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned
I learned that responsiveness is about paying close attention to details. 
I usually like using display-flex, justify-content-center and align-items-center to center my work but that usually required a widtha nd height which could affect responsive behaviour. I stuck with margin-auto for x axis and a percentage like 6% for y axis
display: flex;


```html
 <div class="body"> </div>
```
```css
.body {
	/* width: 100%; */
	width: 70%;
	display: flex;
	justify-content: center;
	align-items: center;
	margin: 7% auto;
	padding: 0rem 1rem;
}
```

### Continued development
I want to start focusing on working with grid, rather than flex


### Useful resources

- https://www.w3schools.com/ - This helped me to check out the best method to use for defining widths. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@Tamarapreye-M](https://www.frontendmentor.io/profile/Tamarapreye-M)
- Twitter - [@tamara_fav](https://www.twitter.com/tamara_fav)


## Acknowledgments
I worked on this all by myself but would not have made it without the help of a few friends and online resources in previous projects

