jquery.horizonScroll.js - Horizontal Scrolling (Paging) Websites
=======================
This is a jQuery plugin which allows for websites to page(scroll by set width) left and right horizontally. Horizontal scroll sites offer a new and unique way to develope sites! Check it out and give feedback! THX

Demo
=======================
Click here for the [demo](http://trgraglia.github.io/jquery.horizonScroll.js/demo/index.html)

Usage
=======================
Initial usage. All elements specified by the selector become a page.
```javascript
$('selector').horizon();
```

If you do not want to use jquery.swipeTouch.js for swipe left and right:
```javascript
$('selector').horizon({swipe: false});
```

You can invoke a left page scroll or right page scroll. This helps if you would like to bind to additional elements on the page.
The selector here is ignored.
```javascript
$(document).horizon('scrollRight');
$(document).horizon('scrollLeft');
```

