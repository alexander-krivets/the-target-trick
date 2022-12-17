# the-target-trick

##:target

##The :target CSS pseudo-class represents a unique element (the target element) with an id matching the URL's fragment.

    /* Selects an element with an ID matching the current URL's fragment */

    :target {
      border: 2px solid black;
    }

##For example, the following URL has a fragment (denoted by the # sign) that points to an element called section2:

    http://www.example.com/index.html#section2

##The following element would be selected by a :target selector when the current URL is equal to the above:

     <section id="section2">Example</section>

##Syntax

    :target
