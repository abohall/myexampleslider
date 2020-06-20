# myexampleslider
Recently got permission to share this project with potential employers. This is a vanilla JavaScript slider that was built to replace a jQuery plugin we used. 

It was built for our needs, and now that I've had time to reflect on it, I would make many changes and improvements, but I wanted to run through some example uses. 

Everything you want to be placed in a slider should go into a <template> tag. Each template tag with the class 'tnt-slider-template' is then constructed into a working slider. 
  
<template class="tnt-slider-template">
<img src="../" alt=".."/>
<img src="../" alt=".."/>
</template>
  
As I developed this slider, I used data attributes to control what it did. 

Examples: 
data-arrows: true | false
This could have been handled without the attribute honestly, just based on the count of the items in the slider. Some instances where it was useful was when we wanted autoplay options (ew) and no control. 

data-columns: integer
I used this to change it from a slider that only contained one item, to multiple items on screen. 

This slider was a constantly changing project. Now that I've had time away from it, I would welcome you to contact me so I can explain just what I would love to do with it. In the mean time, I'm developing a new one from scratch based off my first vanilla JavaScript slider!
