favicons
========

Favicon formats and sizes, as well as relevant markup and links so you never have to do this again

modern user agent support markup:  
<pre><code>
&#60;link rel="apple-touch-icon-precomposed" href="apple-touch-icon-152x152-precomposed.png" /&#62;
&#60;link rel="icon" href="favicon-096.png" /&#62;
&#60;!--[if IE]&#62;&#60;link rel="shortcut icon" href="favicon.ico" /&#62;&#60;![endif]--&#62;
&#60;meta name="msapplication-TileColor" content="#fcda3e" /&#62;
&#60;meta name="msapplication-TileImage" content="favicon-144-trans.png" /&#62;
</code></pre>

&#60;link rel="apple-touch-icon-precomposed" href="apple-touch-icon-152x152-precomposed.png" /&#62;  
if you don't care about wpo, ios takes care of everything

&#60;link rel="icon" href="favicon-096.png" /&#62;  
most browsers

&#60;!--[if IE]&#62;&#60;link rel="shortcut icon" href="favicon.ico" /&#62;&#60;![endif]--&#62;  
trident cc

&#60;meta name="msapplication-TileColor" content="#fcda3e" /&#62;  
&#60;meta name="msapplication-TileImage" content="favicon-144-trans.png" /&#62;  
tiles in windows 8. they work best as transparent images, so notice the background color is placed in meta element and actually taken out of the favicon  
  
relevant references:  
http://mathiasbynens.be/notes/touch-icons  
http://tools.dynamicdrive.com/favicon/  
http://www.kevinleary.net/cross-browser-favicons/  
https://gist.github.com/eighttrackmind/7743482
