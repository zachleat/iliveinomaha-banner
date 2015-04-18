iliveinomaha-banner
===================

Retina friendly progressively enhanced banner for iliveinomaha.com

The banner listed on [iliveinomaha.com](http://iliveinomaha.com/spread-the-word.php) is a blurry image on HDPi/retina screens. We can do better!

Idea and original source code from [@mattdsteele](https://github.com/mattdsteele/matthew-steele.com) introduced in his blog post [A Fresh Coat of Paint](http://www.matthew-steele.com/a-fresh-coat-of-paint/).

## [Demo](http://zachleat.github.io/iliveinomaha-banner/example.html)

## Install

### NPM

    npm install iliveinomaha --save

### Or Bower

    bower install iliveinomaha

## Features

* Starts in markup with a normal text link.
* When CSS transforms are supported, positions as a banner in the top left or right corner.
* Does not require JavaScript.

## Markup

Make sure to include the `iliveinomaha.css` stylesheet.

### Top Right Corner

    <div class="iliveinomaha">
        <a href="http://www.iliveinomaha.com">I live in Omaha.</a>
    </div>

### Top Left Corner

    <div class="iliveinomaha left">
        <a href="http://www.iliveinomaha.com">I live in Omaha.</a>
    </div>

## Browser Support

### A-Grade Experience

A blue banner positioned in the top corner. Includes any browser that supports media queries.

* Internet Explorer 9 and above
* Chrome (31)
* Safari (7)
* Firefox (25)
* Opera (12)
* iOS (6)

### C-Grade Experience

A blue link inline on the page.

* Internet Explorer 8 or below
* Opera (9.1)
