# Hands Dirty Boilerplate

#### A simple boilerplate containing the bare tools you need to help you jump straight into rapid prototyping
This boilerplate, largely based on [Zurb Foundation 4](http://foundation.zurb.com/), is designed to let you get your hands dirty when you have an idea. 

## Projects included in the boilerplate
* [Zurb Foundation 4](http://foundation.zurb.com/) (the basis for grid and styling). Currently there are is one main breakpoint at  768px and the projects referenced below have been aligned to that in ('…/css/custom.css'). 
* [responsive-nav](http://responsive-nav.com) by [Viljami Salminen](http://viljamis.com) (because Foundation's nav can be a little fussy and responsive-nav is flexible and lightweight enough to prototype with and ship your final idea to production code without any dependencies should you need to).
* [appendAround](http://https://github.com/filamentgroup/AppendAround) by [Scott Jehl](http://scottjehl.com/). This is a great tool to allow you to swap elements around in your markup and change the order of things for different devices (based on breakpoints and referencing . 
('1. Insert potential element containers throughout the DOM
2. give each container a data-set attribute with a value that matches all other containers' values
3. Place your appendAround content in one of the potential containers
4. Configure your CSS to only display one potential container at a time (and display others depending on @media conditions in your CSS)
4. Call appendAround() on that element when the DOM is ready, and it'll keep itself in a visibile container at all times')
Currently it's dependant on jquery (and Foundation 4 uses Zepto) which I will resolve, but for rapid prototyping is fine for now! :) 
