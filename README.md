# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Live Site URL: [See the live page here](https://kasia307584.github.io/challenge_Profile-Card-Component/)

### The challenge

- Build out the project to the designs provided

## My process

### Built with

- Semantic HTML5 markup
- CSS3

### What I learned

- Use of `<table>` to structure the content (as alternative to flex and grid)

```html
<div class="numbers">
  <table>
    <tr>
      <th>80K</th>
      <th>803K</th>
      <th>1.4K</th>
    </tr>
    <tr>
      <td>Followers</td>
      <td>Likes</td>
      <td>Photos</td>
    </tr>
  </table>
</div>
```

- Use of `backround-attachment: fixed` (to be able to manipulate the position of the background images)

```css
body {
  background-image: url(images/bg-pattern-top.svg),
    url(images/bg-pattern-bottom.svg);
  background-repeat: no-repeat;
  background-position: left -250px top -250px, right -200px bottom -315px;
  background-attachment: fixed;
}
```

- Use of `<main>` semantic tag (to mark the container of the main content of the body)

## Author

- Frontend Mentor - [See my solutions here](https://www.frontendmentor.io/profile/Kasia307584)
