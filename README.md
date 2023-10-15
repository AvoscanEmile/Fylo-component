# Fylo-component
Frontend Mentor is a website where front-end developers get a design and are asked to make it into a page to practice their skills. This repository is my approach for the following design: https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n

If you want to see this repository live you can do it here: https://avoscanemile.github.io/Fylo-component/

**I do not own this design. If you've any questions related to it you should clarify them in the Frontend Mentor website.** 
## CSS features used in this project:
**Grid:** It was necessary to use CSS grid for the section where the amount of space left is described. CSS grid is pretty useful for this "overlapping" layouts.      
**Flexbox:** I mainly use CSS Flexbox for my projects since it's simpler and quicker to use than CSS Grid. The only exception being really problematic situations where you need to force two objects on top of eachother, or really complex grids with multiple aspect ratios.  
**Variables:** CSS Variables make it way simpler to work with colors, font weights, font sizes, font familys, and shadows. I completely recommend to anyone learning CSS to master them.    
**Functions:** I've used the clamp() function in projects before this, but never the calc(), even less a clamp() inside a calc(). This combination was used to calculate the exact amount of negative positioning needed in the background so the top of the background-img always stayed at the center of the screen, no matter the vh. Simply changing the size of the background-img didn't fit my needs.     
**Triangle Trick:** It's not common to need to make a triangle in CSS. Nevertheless, a quick ways of doing this is having an object that has no height or width, but that has a border specified with 4 values. The variation between these four values changes the shape of the border to fit your needs. In this case the border used provided me with the exact triangle I needed. 
