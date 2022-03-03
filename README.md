# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### What I learned

FLEXBOX:
- flex provides a more efficient way to layout, align and distribute space.
- gives the container the ability to alter its items’ width/height (and order) to best fill the available space (screen sizes). A flex container expands items to fill available free space or shrinks them to prevent overflow.
- flexbox layout is direction-agnostic as opposed to the regular layouts (block which is vertically-based and inline which is horizontally-based). While those work well for pages, they lack flexibility (no pun intended) to support large or complex applications (especially when it comes to orientation changing, resizing, stretching, shrinking, etc.)
- Flexbox layout is most appropriate to the components of an application, and small-scale layouts, while the Grid layout is intended for larger scale layouts.


Main properties of component (parent):
- flex-direction:
    - row (default): left to right in ltr; right to left in rtl
    - row-reverse: right to left in ltr; left to right in rtl
    - column: same as row but top to bottom
    - column-reverse: same as row-reverse but bottom to top

- flex-wrap: by default, flex items will all try to fit onto one line. This can allow the items to wrap as needed with this property.

- flex-flow: combination of 2 above.

- justify-content: aligning along main axis.

- align-items: aligning along cross axis (perpendicular to main axis).

- min-height: 100vh - this puts the child vertically centered on screen.

Styling the child:
- margin: auto - this centers the child on both main and cross axis.


HOVER STATES:
- changing the background / text colour
- changing visibility of an svg

Other things I learnt:
- making an image round
- hr tag, i.e. line separating nearby divs
- aligning image and text centrally
- responsive design - @media query. Although the sizes are fixed - can use percentages next time.


### Useful resources

- [CSS Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me for Flexbox.
