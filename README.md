# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./screenshot.png)

### Links

- Live Site URL: [GitHub Pages link](https://kasia307584.github.io/challenge1/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

- Use tables to structure the content (in simple layout, as alternative to flex and grid)

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

- Use `backround-attachment: fixed` (to be able to manipulate the position of the background)

```css
body {
  background-image: url(images/bg-pattern-top.svg),
    url(images/bg-pattern-bottom.svg);
  background-repeat: no-repeat;
  background-position: left -250px top -250px, right -200px bottom -315px;
  background-attachment: fixed;
}
```

- Use `position: absolute` combined with other properties (to center content on the page)
- Use `<main>` semantic tag (to mark the container of the main content of the body)

```css
main {
  width: 350px;
  height: 370px;
  margin: auto;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}
```

- CSS can be written whithin the HTML file by using `<style>` tag placed inside `<head>` tag (but creating separate `style.css` file is recommended instead)

## Author

- Frontend Mentor - [My profile page](https://www.frontendmentor.io/profile/Kasia307584)
