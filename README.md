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
- [Author](#author)



## Overview

### Screenshot

![[Pasted image 20231227004244.png]]


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5 
- CSS 

### What I learned

I learned how to use Google Fonts. 
The project need the fonts [Outfit - Google Fonts](https://fonts.google.com/specimen/Outfit) with weight 400 and 700.
Firstly I link them to the HTML, it's quite easy because you can copy them from the webpage's top-right corner —— the bag logo which means "View selected families" after you selected the fonts which fit your weight need.
Then, write css, this step need write font-weight attribute with correspoding value, but there is little difference between the two values displayed on the page, so I change the value to 100 and 900, it became more noticeable, and I learned that this way of writing is correct.

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
```
```css
#first {
	font-family: 'Outfit', sans-serif;
	font-weight: 700;
	font-size: 18px;
}
#last {
	font-family: 'Outfit', sans-serif;
	color: hsl(212, 45%, 89%);
	font-weight: 400;
	font-size: 14px;
}
```

### Continued development

I don't know the value of font-size is right or not. 


## Author

like1sky
1:01 2023/12/27 