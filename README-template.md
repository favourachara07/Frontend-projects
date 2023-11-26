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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](http://127.0.0.1:5500/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex


### What I learned

I was able to strengthen my memory and my mind on the creation of this boxes that are used from Shopping platforms to other areas

```html
<div class="qr_container">
    <div class="qr_box">
      <div class="qr_img"><img src="images/image-qr-code.png" alt=""></div>
      <div class="text">Improve your front-end skills by building projects
        <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
      </div>
    </div>
  </div>
```
```css
.qr_container {

    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: hsl(212, 45%, 89%);
    display: flex;
}

.qr_box {
    margin: auto auto auto auto;
    border: 2px solid rgb(255, 252, 252);
    border-radius: 20px;
    background-color: hsl(0, 0%, 100%);
    width: 16.5rem;
    position: relative;
    text-align: center;
    color: hsl(218, 44%, 22%);
    box-shadow: 0px 9px 17px 0px hsla(219, 15%, 55%, 0.274);
    padding-bottom: 2.5rem;
}
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

I wish to become better and more experienced in the making of resusable CSS classes to make my css codes more simplified and shortened for my benefit. I also wish to know what CSS properties will best be assigned for a task

### Useful resources

- [Visual Studio Code and it extensions](https://www.example.com) - This application and its packages helped me to organize my code. I also liked this application and will always use it going forward.


## Author

- Website - [Favour Achara](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**


