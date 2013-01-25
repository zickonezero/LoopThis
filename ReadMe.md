# What does this do?: 
This plugin creates an infinite animation loop with two parameters:  
-animation type (in this case 'opacity')  
-duration of animation

## How do I use it?
For each element you want to run the plugin on, give it a class of "loopThis":

`<span class="loopThis"></span>`  
  
Then create the function call at the very bottom of the code:
  
`$('.loopThis').loopThis();`  

Check out the [demo](http://jsfiddle.net/ZICKONEZERO/SSrU7/7/). 

### Requirements:
jQuery 1.7.2

### Supported Browsers:
Chrome  
Safari  
Firefox  
Opera  
IE 7 - 9