This is a solution to the [Intro section with dropdown navigation challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/intro-section-with-dropdown-navigation-ryaPetHE5). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents
  - [The challenge](#the-challenge)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](I learnt a lot about how to create )
  - [Continued development](#continued-development)
  - [Useful resources](Stack-overflow, MDN    documentation, W3Schools)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)


### The challenge

Users should be able to:

- View the relevant dropdown menus on desktop and mobile when interacting with the navigation links
- View the optimal layout for the content depending on their device's screen size
- See hover states for all interactive elements on the page


## My process
-- I started off with making a little wireframe of the project on my sketchbook.
-- I proceeded to write my HTML code in my codeply account, and after satisfying myself with it, I moved down to atom IDE, where I completed the rest of the code.
I created my CSS file and started styling!

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Bootstrap5
- Desktop-first workflow
- [jquerry](https://reactjs.org/) - JS library
- [Font Awesome](https://fontawesome.com/) - For little icons
- [Google fonts](https://fonts.google.com/) - For Fonts


### What I learned

1) Learning more about the CSS flexbox, which I had to use in my media breakpoint.
2) Using the picture tag for the first time n HTML.
3) Understanding the bootstrap nav-bar and drop-down menu class names.
4) Learning to wireframe, such that I have been able to plan out a website on a piece of paper before going ahead to start designing.

```html
<picture>
    <source media="(min-width:900px)" srcset="images\image-hero-desktop.png">
    <source media="(max-width:800px)" srcset="images\image-hero-mobile.png">
    <img class="big-image" src="images\image-hero-desktop.png" alt="image">
</picture>
```
```css
.row {
    flex-direction: column-reverse;
    row-gap: 3rem;
}
```


### Continued development

1) CSS flexbox, and grid system.
2) a lot more bootstrap.
3) Learning responsiveness without the use of so much media queries.



### Useful resources

- [Bootstrap documentation](https://getbootstrap.com/) - This helped me for really Understandingwhat bootstrap class names I needed at each point. I really liked this pattern and will use it going forward.
- [W3Schools documentation on the HTML picture element](https://www.w3schools.com/tags/att_source_srcset.asp) - This is an amazing article which helped me finally understand how to upload multiple images for different screen sizes. I'd recommend it to anyone still learning this concept.


## Author

- LinkedIn - [Dumebi Okolo](www.linkedin.com/in/dumebi-okolo)
- Frontend Mentor - [@Dumebii](https://www.frontendmentor.io/profile/Dumebii)
- Twitter - [@DumebiTheWriter](https://twitter.com/DumebiTheWriter)


## Acknowledgments

I really want to thank Kayode, for hoping on those long calls with me to explain concepts that were previously difficult for me to understand, and also for the patience to teach me.
