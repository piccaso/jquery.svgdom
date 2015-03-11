# jquery.svgdom
Support dom operations on SVG Elements with jQuery
derived from [jQuery SVG](https://github.com/kbwood/svg) by [Keith Wood](http://keith-wood.name/)

jQuery [does not support SVG Elements](http://contribute.jquery.org/wont-fix/#svg-vml-or-namespaced-elements-bugs), this library compensates that by augmenting the following jQuery functions:

 - [.addClass()](http://api.jquery.com/addClass/)
 - [.removeClass()](http://api.jquery.com/removeClass/)
 - [.toggleClass()](http://api.jquery.com/toggleClass/)
 - [.hasClass()](http://api.jquery.com/hasClass/)
 - [.attr()](http://api.jquery.com/attr/)
 - [.removeAttr()](http://api.jquery.com/removeAttr/)

### Supported Browsers
Modern Browsers that support inline SVG's.
For IE that means 9+.
