# Frontend Mentor - Tip calculator app solution

![Design preview for the Tip calculator app coding challenge](./design/desktop-preview.jpg)
This is a solution to the [Tip calculator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/tip-calculator-app-ugJNGbJUX). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Welcome! 👋
## Table of contents

This is a challenge from Frontendmentor.io
Want some support on the challenge? [Join our community](https://www.frontendmentor.io/community) and ask questions in the **#help** channel.
- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview
## The challenge

The challenge is to build out this tip calculator app and get it looking as close to the design as possible.

### Screenshot
![](images/screencapture-127-0-0-1-5500-index-html-2025-04-30-00_18_59.png)

### Links
- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Tip-Calculator-App](https://tip-calculator-app-fash-mayors-projects.vercel.app/)

## My process
### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned
One major issue I ran into was clearing the values of the numbers in the textboxes, but I could work through it by resetting each of them to default values.
```js
document.querySelector(".reset").addEventListener("click", () =>{
    total_bill.value = '';
    total_people.value = '';
    tip.textContent = '0.00';
    amount.textContent = '0.00';
})
```
### Continued development
I'm going to keep my focus on my frontend. I want to build scalable and functional sites from scratch. I would start by solidifying my JavaScript and then diving into frameworks.

## Author
- Frontend Mentor - [@Fash-Mayor](www.frontendmentor.io/profile/Fash-Mayor)
- Twitter - [@_FashMayor_](https://www.twitter.com/_FashMayor)
