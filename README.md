PlaceholderSupport
================
Adds a fallback for browsers that do not support the placeholder attribute.<br>
Probably the most simple solution for this out there.<br>
I found many others where you need extra CSS. This is so simple that you just have to call the class and you have placeholder support for all browsers!

<b>Published under the MIT-License</b>.

![Screenshot](https://github.com/frozeman/PlaceholderSupport/raw/master/screenshot.png)

How to use
----------
Just add the PlaceholderSupport.js to your website and call:


    #JS
    window.addEvent('domready',function(){

      new PlaceholderSupport();

    });


Will add placeholder functionality to all inputs and textarea elements with a "placeholder" attribute.


    #JS
    window.addEvent('domready',function(){

      new PlaceholderSupport('input.myInputWithPlaceholder');

    });


Will add the placeholder only to inputs with the class "myInputWithPlaceholder". But this input needs also a placeholder attribute with a text!