How Foundation 5 handles IE lte9 support
====

"//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.6.2/html5shiv.js" <br>
"//s3.amazonaws.com/nwapi/nwmatcher/nwmatcher-1.2.5-min.js"<br>
"//html5base.googlecode.com/svn-history/r38/trunk/js/selectivizr-1.0.3b.js"<br>
"//cdnjs.cloudflare.com/ajax/libs/respond.js/1.1.0/respond.min.js"<br>
<br>
http://foundation.zurb.com/forum/posts/241-foundation-5-and-ie8

==
Guidelines CSS Wizardy
==
http://cssguidelin.es/#support-the-guidelines

==
jQuery presentation
==
http://www.slideshare.net/dcneiner/jquery-nuts-bolts-and-bling

==
HTML5 template boilerplate
==
https://github.com/dcneiner/html5-site-template



==
draft
==
1. use namespace function to create object
2. use ifee for autoaticly create api object
3. use revealing module pattern
4. use helper methods rather then the for loop
5. add init function at the bottom of method, right before return statment
6. add main variables at the top of the method
7. use ES6 syntax with transpiler
8. always check if variables are available (typeof checking, lngth checking)
9. when iterating over array always use plural/singular naming convention e.g items.forEach(item)
10. use Web APi  https://developer.mozilla.org/pl/docs/Web/API
11. use native js firtst
12. use _underscore helper function then
13. use jQuery when nothing other helps :)
14. use comments to point out logic
15. use const & let rather then var
16. prefer adding/removing css classes to perform animation/transition rather then using .hide, .show, .fadeId etc.
17. add callbacks to methods?
18. use promises?
19. most uses native version of jQuery => forum
20. use jasmine for unit tests
21. use nightwatch for e2e test
22. use _defaults to merge defaults object
23. this → bind this, loosing this in function obj, this in fat arrows, this 4 ways to checkit
24. prototypes
25. browser bottlenecks
26. ajax requests handling
27. use devtools to inspect enp.APP
