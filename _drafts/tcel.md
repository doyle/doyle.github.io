---
layout: post
title:  Introducing TCel
date:   2013-12-23 11:33:01
categories: software development frontend html css
---

## In the beginning

This is the workflow I used to use to make websites:

1. A designer provides me with a pdf of what s/he wants the page to look like
1. I open the page in Preview
1. I place Preview alongside the in-progress webpage 
1. Look at the designer's image on the left of the screen
1. Make a change in the Chrome inspector that moves the in progress website 
closer to the image
1. Repeat the above two steps until I don't care anymore
close to the designer's original vision
1. Call it done / convince the designer that "pretty close" is as good as pixel perfect

Naturally I believed this to be the optimal workflow until I found myself speaking
to a friend of mine who describe a tool he had been working on that caused 
me to have a "you mean there's a easier way!" moment.

![Homer squeezing an orange with his forehead](/images/homer_juice.jpg)

## TCel

At its core TCel is a very simple application. Much like Preview it gives
one an image in a window. However, TCel has a few enhancements which 
simplify the frontend engineer's life:

1. Transparency

TCel allows the programmer to adjust the transparency of of an image. This means
the programmer can put the source image on top of the website in order to 
see the differences. This reduces the amount of guess work and measurements
that need to be used in order to make the source and site match.

2. Mouse Intercepts

TCel lets the programmer disable mouse intercepts. This means the programmer
can overlay the image over the website and still click on the website
beneath it to use the inspector. This lets the programmer adjust the website
until there are no visible differences.

3. Inverted Colors

Sometimes even when overlaying a partially transparent image it can be difficult
to see if the fine differences (think black text on black text). When one inverts 
the image the small differences become much more apparent.

Now, with TCel my workflow is the following:

1. Import the image from my graphic designer into TCel
1. Make the image partially transparent
1. Overlay the image on the in-progress website
1. Disable mouse intercepts in TCel
1. Use the inspector to adjust the website until it matches the image
1. Invert TCel to verify that I missed no subtle differences

The end result is that I create a higher quality website in less time while
frustrating myself less.


TCel is cheap and makes your life easier find it in the 
[App Store](https://itunes.apple.com/us/app/tcel/id603009251?mt=12).
