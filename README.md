# Frontend Mentor – Profile Card Component Solution

This is my solution to the **Profile Card Component** challenge on [Frontend Mentor](https://www.frontendmentor.io/).  
The challenge helped me improve my **HTML and CSS skills** by building a responsive profile card with visual hierarchy, accessibility and clean component layout.

## Table of Contents
- [Overview](#overview)  
- [The Challenge](#the-challenge)  
- [Design](#design)  
- [Links](#links)  
- [My Process](#my-process)  
- [Built With](#built-with)  
- [What I Learned](#what-i-learned)

## Overview
This project is a **profile card UI component** that displays user information such as profile image, name, age, location and social stats (followers, likes and photos).

The interface features:
- A clean and minimal card layout  
- A responsive and centered design that adapts to screen size  
- A user avatar overlapping a patterned header background  
- Visual consistency using CSS variables and typography imported from Google Fonts  

## The Challenge
Users should be able to:

- View the optimal layout for the card depending on their device’s screen size  
- Recognize a clear visual hierarchy between profile details and statistics  

## Design
### Desktop Design
![Desktop Design](./design/desktop-design.jpg)

### Mobile Design
<img src="./design/mobile-design.jpg" width="200px" alt="Mobile design layout">

## Links
- [GitHub Repository](https://github.com/mlopezl/my-version-of-profile-card-component-challenge)  
- [Live Demo](https://mlopezl.github.io/my-version-of-profile-card-component-challenge/)

## My Process
1. Started by analyzing the original design and identifying key layout sections: header, profile picture, user information and statistics.  
2. Built a semantic and scalable structure using `<article>`, `<header>` and `<footer>`.  
3. Imported typography from Google Fonts and applied consistent font sizing and weight.  
4. Defined CSS variables in `:root` to maintain a cohesive color system across the card.  
5. Styled background images positioned with `position: fixed` to recreate the abstract design.  
6. Used **Flexbox** and **CSS Grid** to align and distribute internal components cleanly.    
7. Implemented a simple responsive adjustment through a media query for smaller screens.

## Built With
- HTML5  
- CSS3  
- Flexbox  
- CSS Grid  
- Google Fonts  
- CSS Variables  

## What I Learned
- How to structure a reusable UI card component using **semantic HTML**.  
- How to center content using **Grid layout** and combine it with Flexbox inside sections.  
- How to use **CSS custom properties** for theme consistency and easier maintenance.  
- How to overlap elements visually using **negative margins** and border styling.  
- How to scale a layout down for mobile devices with small visual changes rather than a full redesign.

