---

layout: presentation
title: Touchy-feely development

---

# _Touchy-feely development_

Slides online @ [bit.ly/touchydev](http://bit.ly/touchydev)

## Dave DeSandro

+ [@desandro](http://twitter.com/desandro)
+ Front-end developer
+ Day job [nclud](http://nclud.com)
+ [Masonry](http://masonry.desandro.com)

## [nclud.com](http://nclud.com) v3

+ Lots of awesome HTML5 features
+ But everyone loves the logo spinner

## Delightful interactions

+ [Nick Kwiatek](sites/nkwaitek.html)
+ [Matrix sequencer](http://projects/touchy-feely-dev/sites/Matrix.swf)
+ [Fancy scrollers](http://delicious.com/desandro/fancyscrolling) like [Nike Better World](sites/nikebetterworld.html) by Ian Coyle and Duane King

## Why are these compelling?

+ Unique to the interactive medium
+ Could not be achieved in a book, movie, song
+ _Require_ a user
+ _Reward_ participation
+ Immediate

## What is the web?

+ Humanity's greatest library
+ Our best tool
+ The web should be a playground too
+ A place for imagination

## Drawing on the Right Side of the Brain

+ by Betty Edwards
+ ![Drawing on the Right Side of the Brain](img/drawing.jpg)
+ On surface level, a drawing tutorial
+ Why can't everybody draw?

## Your two brains

<div class="two-col clearfix">

  <div class="col">
    <h3><em>Left</em></h3>
    <ul>
      <li>order</li>
      <li>sequence</li>
      <li>rational</li>
      <li>language</li>
      <li>grids and tables</li>
    </ul>
  </div>

  <div class="col">
    <h3><em>Right</em></h3>
    <ul>
      <li>chaos</li>
      <li>happenstance</li>
      <li>emotional</li>
      <li>imagery</li>
      <li>blobs and webs</li>
    </ul>
   </div>

</div>

+ L-mode dominates
+ R-mode must be nutured

## The web, land of the L-mode

+ ordered lists
+ grids
+ everything has rationale

## Front-end development

+ Capital city of L-mode
+ a.k.a _Squaresville_

## Developer's dilemma

+ Stuck in L-mode
+ Work all day with code
+ order
+ process
+ Visual designers do 'creative thinking'
+ How can we escape?
+ How can we be more?

## Growing

+ Re-imagine the role of the front-end developer
+ Being expressive
+ Getting in touch with your inner artist

## The front-end _artist_

+ What would a front-end artist do?
+ Engaging users on another level
+ More than making brochures
+ More than rote presentation
+ Make people _feel_ something
+ Get an emotional reaction

## But today...

+ Technology isn't just there yet
+ Tools we have weren't designed for artists
+ They were designed for computers

## By hook or by crook

By any means necessary, get it done

![The Beatles](img/beatles.jpg)

+ Build a library of hooks

## The front-end artist's touchy-feely toolkit

+ Tools and techniques we'll need to make evocative interactions

## JavaScript

+ All about behavoir

## Animation

+ Nothing in nature instantly appears
+ Everything has motion
+ Carries a lot of implicit information
+ Tells a (small) story
+ Stories are how we understand our world
+ Best (cheapest) way to get a _whoa_
+ ![Keanu whoa](img/keanu-whoa.jpg)
+ ![Keanu brain](img/keanu-brain.jpg)
+ ![Keanu in Point Break](img/keanu-sezzy.jpg)
+ ![Conspiracy Keanu](img/conspiracy-keanu2.jpg)
+ ![Conspiracy Keanu](img/conspiracy-keanu3.jpg)


## Understanding frame-based JS animation

+ Perform an operation
+ Wait
+ Perform another operation
+ Repeat

{% highlight javascript %}

var t = 0;

function move() {
  // increment
  t++;
  // apply changes
  element.style.left = t + 'px';
  // do it again in a lil bit
  setTimeout( move, 16 );
}

{% endhighlight %}

See example [move.html](move.html)

+ Same concept used throughout every JavaScript animation library
+ jQuery `.animate()`
+ `requestAnimationFrame`
+ Fundamental component of all the other techniques

## Non-JS animation

+ CSS transitions
+ CSS `@keyframes` animations
+ SVG path animation
+ Animated GIF
+ [bottom-of-the-ninth.com](http://www.bottom-of-the-ninth.com/) by Ryan Woodward
+ [House Industries Photo Lettering - How to](http://www.photolettering.com/how_to/)

## Reverse Transformation

+ Remember that [Jamiroquai - Virtual Insanity video](http://www.youtube.com/watch?v=4JkIs37a2JE) from a while back?

<iframe width="420" height="315" src="http://www.youtube.com/embed/4JkIs37a2JE" frameborder="0" allowfullscreen="allowfullscreen"> </iframe>

+ Applying a transformation on a child
+ then apply the reverse transformation on its parent
+ [Zoomooz](janne.aukia.com/zoomooz/) by Janne Aukia
+ [nclud.com/contact](http://nclud.com/contact) map

See example [corner-hide.html](corner-hide.html)

## Image manipulation

+ `<canvas>`
+ [Rally Interactive](http://beta.rallyinteractive.com/)
+ Server-side solutions like PHP GD, ImageMagick
+ CSS filters

## Particles

+ A collection of items
+ Each item has same behavoir, but different properties

See example [jsfiddle.net/desandro/mNtrc/](http://jsfiddle.net/desandro/mNtrc/)

<iframe style="width: 100%; height: 300px" src="http://jsfiddle.net/desandro/mNtrc/embedded/result,js/" allowfullscreen="allowfullscreen" frameborder="0"> </iframe>

See example [desandro.com/demo/2011/undulate-graphene/](http://desandro.com/demo/2011/undulate-graphene/)

+ Perceived complexity, simple execution
+ This is what computers accel at
+ Parallax

## Expertise

+ Knowing your tools
+ Confronting new problems makes you reach for new tools

## Coloring outside the lines

+ [Scrollability](http://joehewitt.github.com/scrollability/tableview.html) by Joe Hewitt. See [details](http://joehewitt.com/2011/10/05/fast-animation-with-ios-webkit)
+ [Morf.js](http://www.joelambert.co.uk/morf/) by Joe Lambert
+ Dynamically generate and inject custom `@keyframes` styles into pages

## Interactive

How will you get the user involved?

+ click / touch
+ mousemove / touchmove
+ hover
+ scroll
+ keyboard
+ multi-touch gesture
+ device orientation & gyroscope


## Selling it 

+ Take initiative
+ It's not a line-item on the proposal
+ Make prototypes, experiment

## A final touchy-feely note

+ We work on machines
+ ...in the language of machines
+ ...to be intepreted and displayed by other machines
+ But in the end, it's for people

## Build for people
