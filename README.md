


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
<<<
pobranie kolekcji elementów z dom
=>
podpięcie eventów
=>
chodzenie po drzewie dom
=>
pobieranie informacji z data atrybutów
=>
iterowanie po kolekcjach
=>
ajax requests (ok)
=>
pobieranie informacji o stylach elementów / pozycjach
>>>
20. use jasmine for unit tests
21. use nightwatch for e2e test
22. use _defaults to merge defaults object
23. this → bind this, loosing this in function obj, this in fat arrows, this 4 ways to checkit
24. prototypes
25. browser bottlenecks
26. ajax requests handling
27. use devtools to inspect enp.APP



==
todo & current
==

1. vue.js
2. react
3. meteor.js
4. electron
5. jenkins
6. es6
7. mongodb
8. redux


==
patterns
==

1. Namespacing Pattern
2. Dependency declaration pattern
3. Constructor Pattern
2. Module Pattern
3. Revealing Module Pattern
4. Singleton Pattern
5. Observer Pattern (pub/sub)
6. Mediator Pattern
7. Prototype Pattern
8. Command Pattern
9. Facade Pattern
10. Factory Pattern
11. Mixin Pattern
12. Decorator Pattern
13. Flyweight Pattern
14. Sandbox Pattern
15. AMD
16. Common JS
17. jQuery Plugin Design Patterns
18. Lazy Initialization Pattern
19. Proxy Pattern
20. Builder Pattern
21. Composite Pattern
22. Adapter Pattern


==
antipatterns
==

1. Polluting the global namespace by defining a large number of variables in the global context
2. Passing strings rather than functions to either setTimeout or setInterval as this triggers the use of eval() internally.
3. Modifying the Object class prototype (this is a particularly bad anti-pattern)
4. Using JavaScript in an inline form as this is inflexible
5. The use of document.write where native DOM alternatives such as document.createElement are more appropriate. document.write has been grossly misused over the years and has quite a few disadvantages including that if it's executed after the page has been loaded it can actually overwrite the page we're on, whilst document.createElement does not. We can see here for a live example of this in action. It also doesn't work with XHTML which is another reason opting for more DOM-friendly methods such as document.createElement is favorable.



===
http://intridea.github.io/sketch.js/lib/sketch.js
https://github.com/niklasvh/html2canvas
http://www.kubilayerdogan.net/html2canvas-take-screenshot-of-web-page-and-save-it-to-server-javascript-and-php/
