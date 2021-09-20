# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

I added a screenshot of mobile and desktop design found in screenshot folder.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [SASS](https://sass-lang.com/) - CSS Preprocessor
- [NPM] - Package Manager

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
			<main>
					<div class="intro">
							<h1> 10,000+ of our users love our products.</h1>
							<p class="lead"> We only provide great products combined with excellent customer service. See what our satisfied customers are saying about our services.</p></div>
						<ul class="ratings flow-content">
							<li class="rewiew">
								<div class="stars" aria-hidden="true">
									<img src="assets/images/icon-star.svg" alt="star">
									<img src="assets/images/icon-star.svg" alt="star">
									<img src="assets/images/icon-star.svg" alt="star">
									<img src="assets/images/icon-star.svg" alt="star">
									<img src="assets/images/icon-star.svg" alt="star">
								</div>
							Rated 5 Stars in Reviews</li>
						</ul>
	 		<ul class="quotes split"> 
	 			<li><blockquote>
				 	<div class="split a-center">
				 		<img src="assets/images/image-colton.jpg" alt="colton">
					 	<div>
						 	<p class="name">Colton Smith</p>
						 	<p class="status">Verified Buyer</p>
					 	</div>
				 	</div>
            <p class="quote">"We needed the same printed design as the one we had ordered a week prior. Not only did they find the original order, but we also received it in time. Excellent!"</p>			 
						</blockquote>
					</li></ul></main>
```
```css
@media (min-width: 50em){

		main{
			grid-template-columns: 1fr 1.5fr;
			text-align: left;
		}
		.intro{
			grid-column: 1 / 2 ;

		}
		.ratings{
			grid-column: 2 / 3 ;
			align-self: center;
		}
		.quotes{
			grid-column: 1 / -1 ;
		}
	}
```
```js

```




### Useful resources

- [@use](https://sass-lang.com/) - This helped me for at-rules. The difference between node-sass and dart sass
- [grid]https://developer.mozilla.org/en-US/docs/Web/CSS/grid) - This is an amazing article which explained the Grid layout and its properties.

## Author
- Frontend Mentor - [@erickamae-mateo](https://www.frontendmentor.io/profile/erickamae-mateo)

## Acknowledgments

	Special thanks to Mr. Kevin Powell for his free tutorial. I learned a lot from watching your videos.  They are informative and useful provided with examples and a clean explanation.
https://www.kevinpowell.co/
