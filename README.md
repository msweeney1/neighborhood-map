# Neighborhood-map
<img src="img/logo.png" alt="">

It says "neighborhood map", but this map actually shows the area where I grew up instead. I spent a lot of time around these places, so I decided it was more appropiate. The village of Chittenango NY is not big but I liked living there.

The [Live project](http://msweeney1.github.io/neighborhood-map/) is hosted in github pages.

This is my fifth project towards my Front-end Nanodegree.

How do I see it in action?
-------------------------------------
You can either check it at
```
http://msweeney1.github.io/neighborhood-map
```

Or you can clone this repository by running the following command
```
git clone https://github.com/msweeney1/neighborhood-map
```
Modify apiKey [js/app.js](js/app.js) (line 21) with your [Google Maps API Key](https://developers.google.com/maps/documentation/javascript/tutorial#api_key) and open [index.html](index.html) in the root folder with your browser.
If you want, after this you can run on the command line
```
grunt
```
and open [dist/index.html](dist/index.html) for the production ready app.

Can I tweak it?
-------------------------------------
Sure! You'll need to install [Node.js](https://nodejs.org) and [Grunt](http://gruntjs.com/getting-started). Then, just clone this repository and install the dependencies from the command line with
```
npm install
```
The heart of the application is [app.js](js/app.js), so it's probable you'll want to modify it. Check the documentation on [more info on app.js](js/AppJsInfo.md) if you need it explained further.

I do not recommend modifying the contents of [dist](dist), because these will be modified each time you run grunt.

Updates

I corrected the issue in app.js where the wikipedia ID and foursqaure IP for some locations were pointing to areas in Ciudad Obregon so that they now point to the locations in Chittenango NY.

I corrected the css file names so that the links in index.html now point to the correct css files.

I corrected the error handling in the app.js file.

References
-------------------------------------
The code in this repository (or that was in this repository at some point) as well as the ideas put in practice here were possible thanks to the authors of the following:
* [Some map inspiration that got me started](http://codepen.io/digsublime/pen/vERPxW)
* [Responsive, Retinafied Google Map Images](http://webdesigntutsplus.s3.amazonaws.com/tuts/365_google_maps/demo/index.html)
* [Adaptive Maps](http://bradfrost.com/blog/post/adaptive-maps/)
* [Google Maps UI](https://maps.google.com/maps)
* [Google Maps JavaScript API v3](https://developers.google.com/maps/documentation/javascript/tutorial)
* [Knockout documentation](http://knockoutjs.com/documentation/introduction.html)
* [Foundation docs](http://foundation.zurb.com/docs)
* [Animated CSS3 Notification Bar](http://martinivanov.net/2013/12/20/animated-css3-notification-bar/)
* [Knockout Live Search example](https://gist.github.com/hinchley/5973926)
* [Awesomplete by Lea Verou](http://leaverou.github.io/awesomplete/)
* [You Might Not Need JQuery](http://youmightnotneedjquery.com/)
* [Working with an API | Bypassing the same-origin policy](http://jsandjq.tumblr.com/post/100002927594/working-with-an-api-bypassing-the-same-origin)
