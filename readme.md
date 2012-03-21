# [GrindMedia Frontend Boilerplate](https://github.com/jmayfield/GrindMedia-Frontend-Boilerplate)

In the wake of healthy debate and collaboration, and in the spirit of becoming better at what we do each passing day; I thought it might be beneficial to to have some sort of "standard" boilerplate for frontend development on future projects. The goal is to collaborate and settle on a set of consistent, reusable elements that we can all become familiar with and build from. This project isn't meant to be an HTML5 Boilerplate clone, it's meant to be a slightly built-out kit with Grind specific re-usability in mind, ie. layout, header, footer, navigation, modules, etc.

Ideally, when we find ourselves with a bit of downtime, after we've discussed zombies, video games, helicopters, winning the lottery and making fun of Internet Explorer, we could spend some time discussing what we think might actually be beneficial for our group in a frontend boilerplate.


## What's Included

I used [Paul Irish's](http://paulirish.com/) great [HTML5 Boilerplate](http://html5boilerplate.com/) as a starting point with [Normalize](http://necolas.github.com/normalize.css/) and [Modernizr](http://www.modernizr.com/) to help with degradation and cross-browser compatibility. I've left all of the HTML5 Boilerplate commenting intact so that it's easy to see what's going on right off the bat, but we can strip all the commenting as this moves along. Speaking of stripping, there are a lot of extraneous files included as of now. I've done this on purpose, because I'd rather strip out what we don't need and boil it down to something everyone can use quickly, but I'd like your input on what you think should go. You're telling me you don't want six iOS touch icons? Humph.

I've added a few basic elements right off the bat:

* A 970px container. Our standard as of now.
* Swappable 640px main and 300px sidebar columns. (Not tied to either side of the container)
* Correct use of a few new HTML5 elements in the basic layout as well as WAI-ARIA markup for accessibility.


## Features of HTML5 Boilerplate

Boilerplate is not a framework, nor does it prescribe any philosophy of development, it's just got some tricks to get your project off the ground quickly and right-footed.

* HTML5 ready. Use the new elements with confidence.
* Cross-browser compatible (Chrome, Opera, Safari, Firefox 3.6+, IE6+).
* Designed with progressive enhancement in mind.
* IE-specific classes for easier cross-browser control.
* A default print stylesheet, performance optimized.
* Mobile browser optimizations.
* Protection against any stray `console.log` causing JavaScript errors in IE6/7.
* The latest jQuery via CDN, with a local fallback.
* An optimized Google Analytics snippet.
* Apache server caching, compression, and other configuration defaults for Grade-A performance.
* Cross-domain Ajax and Flash.
* "Delete-key friendly." Easy to strip out parts you don't need.
* Extensive inline and accompanying documentation.


## Features of Normalize.css

Normalize.css is a section of customizable CSS that helps browsers render all elements more consistently and in line with modern standards. The developer researched the differences between default browser styles in order to precisely target only the styles that need normalizing. It's intended to be used as an alternative to CSS resets. It's suggested that you read the Normalize section of the CSS file and consider customizing it to meet your needs. We include the file in the boilerplate with the abaility override the defaults later in the CSS.

* Preserves useful defaults, unlike many CSS resets.
* Normalizes styles for a wide range of HTML elements.
* Corrects bugs and common browser inconsistencies.
* Improves usability with subtle improvements.
* Explains what code does using detailed comments.


## Features of Modernizr

A custom Modernizr build for feature detection is included in the boilerplate. Modernizr is a small JavaScript library that detects the availability of native implementations for next-generation web technologies, i.e. features that stem from the HTML5 and CSS3 specifications. Many of these features are already implemented in at least one major browser (most of them in two or more), and what Modernizr does is, very simply, tell you whether the current browser has this feature natively implemented or not.

* Tests for over 40 next-generation features, all in a matter of milliseconds.
* Creates a JavaScript object (named Modernizr) that contains the results of these tests as boolean properties.
* Adds classes to the html element that explain precisely what features are and are not natively supported.
* Provides a script loader so you can pull in polyfills to backfill functionality in old browsers.


## Contributing

You're all welcome to contribute! This doesn't have to strictly be a frontend endeavor. If anyone feels there are additions they could make that would allow this resource to be more useful to the group as a whole, feel free to fork this Git repository and make changes and requests as you see fit.


## Project information

* Company: [GrindMedia](http://www.grindmedia.com/)
* Source: https://github.com/jmayfield/GrindMedia-Frontend-Boilerplate
* Docs: Coming soon! Maybe.


## License

### Major components:

* jQuery: MIT/GPL license
* Normalize.css: Public Domain
* Modernizr: MIT/BSD license
* HTML5 Boilerplate: Public Domain