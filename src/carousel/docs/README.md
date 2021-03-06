Carousel creates a carousel similar to bootstrap's image carousel.

The carousel also offers support for touchscreen devices in the form of swiping. To enable swiping, load the `ngTouch` module as a dependency.

Use a `<uib-carousel>` element with `<uib-slide>` elements inside it.

### uib-carousel settings

* `interval`
  _(Default: `none`)_ -
  Sets an interval to cycle through the slides. You need a number bigger than 0 to make the interval work.
  
* `no-wrap`
  _(Default: `false`)_ -
  Disables the looping of slides. Setting `no-wrap` to an expression which evaluates to a truthy value will prevent looping.
  
* `no-pause`
  _(Default: `false`)_ -
  The interval pauses on mouseover. Setting this to truthy, disables this pause.
  
* `no-transition`
  _(Default: `false`)_ -
  Whether to disable the transition animation between slides. Setting this to truthy, disables this transition.
  
* `template-url`
  _(Default: `uib/template/carousel/carousel.html`)_ -
  Add the ability to override the template used on the component.
  
### uib-slide settings

* `active`
  _(Default: `false`)_ -
  Sets the slide as the active one.
  
* `actual`
  _(Default: `none`)_ -
  Use this attribute to bind the slide model (or any object of interest) onto the slide scope, which makes it available for customization in the carousel template.
  
* `index`
  _(Default: `none`)_ -
  Use this attribute to change how the slides are ordered.
  
* `template-url`
  _(Default: `uib/template/carousel/slide.html`)_ -
  Add the ability to override the template used on the component.
