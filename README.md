### Desing-room

Design room is static web page designer written in HTML5 , CSS3 and Javascript.However for authentication and 
file generation purposes , it uses PHP  , can be easily ported to client only version.

---

Design room provides canvas which is drag and drop enabled, which means you can freely arrange elements
on canvas anytime you like.Because it is for experimental purposes, canvas size is kept small, to allow room 
for other features.
It has 4 basic set of html elements to start. namely &lt.p&gt; , &lt.div&gt; , &lt.aside&gt; ,  &lt.img&gt;.
Css properties corresponding to these elements are loaded in property pane on right and includes all properties that 
the corresponding element can be styled to.
Images for image tag are uploaded through ajax powered image upload , which is drag and drop enabled too.
All the elements can be resized dynamically at run time using size extenders , appended to bottom right of element.
(take the mouse pointer to bottom right of element and mouse pointer style changes).
*currently resizing and repositioning cannot be executed simultaneously. click the lock in property pane to resize and then unlock pnce resizing is done*.
Design room generates code for the design and can provide zip download for the same.User can also view the code any time they like.

*To run design-room locally , download and place the design-room in your www directory or any other folder according to your php environment,
and make sure curl is enabled , see [this](http://www.tomjepson.co.uk/enabling-curl-in-php-php-ini-wamp-xamp-ubuntu/) and enter the url of design-room in your root directory.*

Credits :  

* [Othenticator](https://github.com/psych0der/Othenticator) for authenticating users 
* [eycon color picker](http://www.eyecon.ro/colorpicker/) as color picker plugin
* [jquery code clean](https://code.google.com/p/jquery-clean/) for tidying html and syntax coloring
* [chardin.js](https://github.com/heelhook/chardin.js) for instruction overlay



---
&copy; mayank bhola 2013
