PlaceholderSupport
================
Adds a fallback for browsers that do not support the placeholder property.
Probably the most simple solution for this out there.
I found many others where you need extra CSS. This is so simple you just call the class and you have placeholder support in all browsers!

How to use
----------
Just add the PlaceholderSupport.js to your website and call:

    #JS
    new PlaceholderSupport();

    or

    new PlaceholderSupport(elements);

Leave the "elements" parameter empty, to add placeholder functionality to all inputs and textarea elements with a "placeholder" attribute.

Otherwise the "elements" parameter can be a string with CSS selectors or an array with elements.