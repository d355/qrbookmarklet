**_NOW SUPPORTS HTTPS SITES WITHOUT WARNINGS_**


&lt;BR /&gt;


**_NOW SUPPORTS GOOGLE MAPS_**

**PLEASE READ MY [RESPONSE](Response.md)**

By placing a "bookmarklet" to this js file, a QR Code will be generated in a lightbox to scan into your mobile device.

clicking anywhere within the body of the document afterwards will remove all instances used for the QR Code.

Create a bookmark on your bookmark bar, and point it to this location.


&lt;BR /&gt;



**javascript:(function(){if(document.getElementById){var x=document.body;var o=document.createElement('script');if(typeof(o)!='object') o=document.standardCreateElement('script');o.setAttribute('src','https://qrbookmarklet.googlecode.com/svn/trunk/qr.js');o.setAttribute('type','text/javascript');x.appendChild(o);}})();**


&lt;BR /&gt;



when you click that bookmark it will generate the QR code for the browsers current URL.


&lt;BR /&gt;



**_Note: If you use a javascript blocking plugin such as NoScript, you will have to whitelist qrbookmarklet.googlecode.com for the QR generation to take place._**