<!-- Please update value in the {}  -->

<h1 align="center">Business Blog Card | devChallenges</h1>

<div align="center">
   Solution for a challenge <a href="https://devchallenges.io/challenge/business-blog-card" target="_blank">Business Blog Card</a> from <a href="http://devchallenges.io" target="_blank">devChallenges.io</a>.
</div>

<div align="center">
  <h3>
    <a href="https://developwebadnan.github.io/business-blog-card-starter-master/">
      Demo
    </a>
    <span> | </span>
    <a href="https://github.com/DevelopWebAdnan/business-blog-card-starter-master">
      Solution
    </a>
    <span> | </span>
    <a href="https://devchallenges.io/challenge/business-blog-card">
      Challenge
    </a>
  </h3>
</div>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Overview](#overview)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Built with](#built-with)
- [Features](#features)

<!-- OVERVIEW -->

## Overview

![screenshot](https://i.ibb.co.com/Kpn3YsS5/screencapture-github-io-2026-10-28-23-46-06.png)

<!--
Introduce your projects by taking a screenshot or a gif. Try to tell visitors a story about your project by answering:

- What have you learned/improved?
- Your wisdom? :)
-->
I think I have improved on my skill of making website responsive. Also, I think I have learnt to use flex properly, especially while aligning the blog card to the center of the section of the website; and hopefully I am also getting better at adjusting width of elements, like the blog card.
### What I learned

<!-- Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge. -->
- I have learnt while working through this project that dealing with an overlay image is not so hard. Similar to other elements of a site, an overlay image also has to be positioned properly and that is enough to make the site appear similar to the provided design, at least for the overlay image part, before thinking about responsiveness.
- Another thing that I have learnt through working with this project that using 'max-content' for the width property of the blog-card div seemed to have done the trick, but this did not work as intended. When we want to make a site responsive, we use the 100% value for the width property of the images used at the site. While making the site responsive on tablet devices, I fell into trouble when I used 100% for the width property of the images inside the blog-card div. Suddenly, the blog-card div started adjusting its width with the width of the image, which started adjusting its width with the width of the screen of the devices (which are available in the devtools). So, I finally figured out that using the max-width property instead of using width: max-content is a work-around.
### Useful resources

<!--
- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.
-->
- [Solution Editor | devchallenges.io | devChallenges](https://devchallenges.io/editor/solution/70135) - The provided resources, designs, typography and colors helped me design my site similar to the provided designs.
### Built with

<!-- This section should list any major frameworks that you built your project using. Here are a few examples.-->

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

## Features

<!-- List the features of your application or follow the template. Don't share the figma file here :) -->

This application/site was created as a submission to a [DevChallenges](https://devchallenges.io/challenges-dashboard) challenge.
- The site contains just a section containing a blog card with an image, an overlay image, a business blog and author info. The site's features are as follows:
 - Responsive on desktop, tablet and mobile devices.
 - Contains an overlay image

## Author

- Website [My Portfolio](https://developwebadnan.github.io/web-dev-portfolio/)
- GitHub [@DevelopWebAdnan](https://github.com/DevelopWebAdnan)
