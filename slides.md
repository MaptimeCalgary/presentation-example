# The presentation template

## MaptimeCalgary
This is the first slide.

_Press `F` to go full-screen._<!-- .element: class="fragment" data-fragment-index="1" -->

_Try moving `RIGHT`._<!-- .element: class="fragment" data-fragment-index="2" -->



## Follow along
These slides are created with Reveal.js + Markdown.

Take a look at the [raw source for the slides](https://raw.githubusercontent.com/MaptimeCalgary/presentation-example/gh-pages/slides.md). The repo can be found [here](https://github.com/MaptimeCalgary/presentation-example).



## This is a new slide
Create these by placing 3 line-breaks in the markdown source.

_From here, you can move `LEFT`, `RIGHT`, or `DOWN`._ <!-- .element: class="fragment" data-fragment-index="0" -->

_Try `DOWN`._ <!-- .element: class="fragment" data-fragment-index="1" -->


## This is a vertical-slide
You make these by placing 2 line-breaks within the source.

Vertical-slides are good for drilling in to topics. Think of it as a _details_ slide. If you're short on time, you can skip past these slides by moving `RIGHT`.



## You can put images in a slide

![alt text](assets/logo.png "Logo Title Text 1")

![external image](https://raw.githubusercontent.com/maptime/maptime.github.io/master/img/xmaptime-logo-web-header-rainbonly.png.pagespeed.ic.sUvy41gYSf.png "External Image Example")



<!-- .slide: data-background="MintCream" -->
## Style

You can style each slide individually.

_Cool background, right?_<!-- .element: class="fragment" data-fragment-index="1" -->
```
<!-- .slide: data-background="MintCream" -->
## Style

You can style each slide individually.
```



## Hey, it even supports code!

```
var marker = L.marker([49, 5.49]).addTo(map);
var polygon = L.polygon([
  [51.509, -0.08],
  [51.503, -0.06],
  [51.51, -0.047]
]).addTo(map);
marker.bindPopup("<b>Hello world!</b><br>I am a popup.").openPopup();
polygon.bindPopup("I am a polygon.");
```



## Want to see something really crazy?

Press `S` to check out the 'Presentation Mode'.

Note:
The idea is that you put the other window on a shared screen, like a projector, and view this screen on your laptop. Btw, this note is only visible to the presenter.



## That's about it

There are a bunch of cool things you can do with **Reveal.js** and **Markdown**.

Check out Reveal.js' [example slides](http://lab.hakim.se/reveal-js/) for more quick examples of what you can do with Reveal.js.  Check out Reveal.js' [Readme](https://github.com/hakimel/reveal.js/blob/master/README.md) and its [wiki](https://github.com/hakimel/reveal.js/wiki) (especially the [Articles & Tutorials](https://github.com/hakimel/reveal.js/wiki/Articles-&-Tutorials) section) for greater detail about using Reveal.js.  

Check out this [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for a quick intro into using Markdown.
