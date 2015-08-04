---
layout: post
title: "A for animation"
date:   2015-08-04 00:36:00
category: SVG SVGfromAtoZ
image: svg-a2z-banner.png
---

So my idea was to have bouncy letters that fell at different times. I tried using just one svg first. It didnt work out so well. So I used one svg per letter.
What you need to do is position each letter absolutely.
Then create a keyframe(I called mine bounce) and change its positioning from your baseline(in my case top: 200) to 0 somewhere around the middle.

I turned the font weight to bold as well towards the middle of the keyframe, this makes it look like it grows bigger and has to fall back down. As you can see I changed the color of the fill throughout the animation.

So youll give each svg its own id and add css animation to it.  They all get the bounce keyframe just different start times spaced out .5s from each other. the ease-in-out transition is nice on this particular animation.  

<p data-height="291" data-theme-id="17558" data-slug-hash="QbJJNa" data-default-tab="result" data-user="loganaaron" class='codepen'>See the Pen <a href='http://codepen.io/loganaaron/pen/QbJJNa/'>A - SVGfromAtoZ</a> by Logan Peterson (<a href='http://codepen.io/loganaaron'>@loganaaron</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

<a href="http://codepen.io/collection/ABNJQQ/">Here is a link</a> to the SVG from A to Z collection on my codepen.

Find out about css animations and keyframes <a href="https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Using_CSS_animations">here</a>.
