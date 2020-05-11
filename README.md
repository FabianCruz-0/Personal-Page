### *I have been developing this page since 2018.*
http://fabiancruz.x10.mx/index.html

![index.](http://fabiancruz.x10.mx/static/page.png "index")

* Almost 80% is interactive.
* Completely responsive design.
* External fonts.
* A lot of  CSS animations (the background is also an infinite CSS animation).
* Jquery.
* Bootstrap.
<hr>

## *The <ins>BIG IDEA</ins> behind my Navigation bar (Nav-bar) Implementation.*

You can see in my page that the navbar it keeps always responsive and the items stay where they should. 


I use the simplest Nav-bar of bootstrap for better manipulation, but ¿What is the problem with that? <br>
That Nav-bar by default have some issues:

* The height isn't responsive.
* The text isn't responsive.
* If I change some values of the text, it lost all of the Nav-bar format by Bootstrap.
* The alignement of the text. The default alignement is all to the left.

The idea and how I fixed.

Since the Bootstrap's items are on an unordened list, I can't manipulate using the *`float`*. <br>
I came up with using **<ins>positive and negative margins with pxiels, viewport width and percentages<ins>**.

The nav-bar "Brand" (My name) have a margin positive to the right, but also a margin negative to the left.

The unordened list  have a margin negative percent to the left.

### *The magic about the use of positive and negative margins with pxiels, viewport width and percentages in the nav-bar:* <br>
Given a positive margin towards the x axis, a negative margin along the same axis, but <ins>**WITH A HIGHER PERCENTAGE**</ins> , it allows a new calculation of the occupied percentage of the screen with respect to the attribute *`viewport Width`* while the screen is getting smaller in width.

<hr>

## What the newest version of my personal page includes:
* 15% of editing visual stuff, it keeps the design, but made it cleaner.
* 25% of improving the performance while you're wathcing it, because of the way that animations were made.
* 60% of improivng the project's structure. it have **<ins>AN INCREDIBLE</ins>** reduction of files and better organization.
![reduccion de documentos.](http://fabiancruz.x10.mx/static/changes.jpeg "reduccion de documentos")