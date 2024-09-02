# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop](image-4.png)
![Tablet](image-3.png)
![Mobile](image-2.png)

### Links
- Live Site URL: [GitHub Page] https://erikcm95.github.io/elearning/

## My process
NOTE!!! Made small changes to design to what I thought looked better. Spacing seemed innefficient in original design provided.

Desktop
- Began by importing all of the text styles into classes to save time. Took 10 mins up front and was a huge time saver in the future.
- Worked from top to bottom, left to right for the elements. The element that gave me the toughest time was the banner. I ultimately ended up going with a position absolute, and fixing the margin on the top right button so it moves with the banner. The skilled logo is set to an 8% left margin so as the page collapses it moves in slightly.
- Did all positioning/sizing using grey background, then transitioned to backgrounds/colors appropriate per style guide.

Tablet
- Once desktop complete, found natural break point with screen width reduction.
- Updated font-presets IAW design
- Display: none desktop banner, display: block tablet banner
- Made necessary margin/padding changes

Mobile
- Found second natural break point.
- Updated font-presets
- Display: none tabletBanner display: block mobileBanner
- Had to move moobileBanner to below text div for proper positioning
- Altered the #callout course div.

Still needs update when I have time
- Right now, as .getStarted Container decreases in size (width is % based), the height increases to fit text, pushing the courses down. Will code to prevent this.

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned
- If an object overflows the body use overflow-x: hidden. This will prevent the scroll bar from appearing at the bottom of the page. 
- Multiple classes can be added to an element via class="class1 class2". Very helpful when there are multiple common sets of properties for an element.
- For elements, using the width: fit-content wiill reduce the width regardless of parent width.

'''Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

```html
```
```css
html {
  overflow-x: hidden;
}

#middleButton {
  background-color: grey;
  width: fit-content;
  padding: 16px 32px;
  border-radius: 30px;
  background-image: linear-gradient(#ff6f48, #f02aa6);
  color: white;
}
```

### Continued development
- index.css looks bulky, if anyone more proficient than I am takes a look and sees ways to slim down the code to make it simpler would love input.
- Margin vs. padding and getting spacing with them...need to improve them. Right now it is a combination of both.

## Author
- Frontend Mentor - [@erikcm95](https://www.frontendmentor.io/profile/erikcm95)
- GitHub - [erikcm95](https://github.com/erikcm95)