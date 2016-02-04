---
layout: post
permalink: /blog/:title
title: Responsive images
date: 2014-11-06
excerpt: If responsive web design is a pleonasm, then from now on responsive images is one too. There’s absolutely no reason not to use them from now on. I’m excited.
----
As most web designers of my generation I didn’t study my profession by designing for screens. I learned graphic design mostly on paper, used glue and scissors, and only barely touched a computer to set type. Not much later though—I was still in school—iMacs took over and very soon I decided to design for screens: mostly dvd interfaces, Flash foolery and web sites.

I was obsessed with the design of interaction that naturally comes with designing for screens. I remember my first hover style on the most ordinary text link. It felt like magic. I couldn’t stop hovering over the text link to see the change in color and shape. It really excited me and honestly: simple things like that still get me hooked up from time to time. 

The active state of a button. A smooth CSS transition that stays out of the way. A form field that reacts rightly. Undoability. The tiny details that make a visitor feel at ease, that make this arduous web thing simpler to navigate.

If these are the little things that make me love this profession, it’s bigger innovations that give me true energy boosts once in a while. There’s only a few I genuinely recall in the past 15 years or so: pure CSS design in the mid 2000’s, mobile and the conforming solution of responsive design a couple of years ago, web fonts also. It’s technologic novelties that truly changed the shape of web design.

And now there’s (link: http://responsiveimages.org text: responsive images). Finally. Can you believe that? They make me feel excited once more. It’s not something that changes our craft the way aforementioned innovations did, I guess therefor it’s too much of a ‘behind the scenes’ thing, but it’s a solution that makes web design live up to its standard again. And that’s important too.

Responsive images solve a huge problem in a way that’s a godsend for web designers: we really don’t have to give it much thought. We just provide browsers all needed details and the browser then finds out what image is best for the user. That decision may be based on many varying factors, it’s up to the browsers to decide: connection speed, screen density, user settings, viewport width, device incapabilities, hell even the presence of a coffee smell if browser devs think that’s appropriate.

I don’t feel the need to go in detail about how it works, you can read up on that [here](http://alistapart.com/article/responsive-images-in-practice), [there](https://dev.opera.com/articles/responsive-images/) and [everywhere](https://dev.opera.com/articles/native-responsive-images/). But I’ve been teaching responsive images in the past few weeks and in doing so I learned it’s not the simplest HTML concept to grasp. It even feels incorrect having to update a HTML attribute’s value every time you decide a CSS media query break point has to change. Yet only by seeing the often massive amount of bytes it skims off the average web page, it’s so worth digging into.

If [responsive web design is a pleonasm](http://thomasbyttebier.be/blog/responsive-web-design-is-a-pleonasm), then from now on responsive images is one too. There’s [browser support](http://caniuse.com/#feat=srcset) and there’s [a polyfill](http://scottjehl.github.io/picturefill/), so there’s absolutely no reason not to use them from now on.