# aspectRatio
Plug-in for keeping aspect ratio of an object, with responsive grid brakepoints

Initialize adding:
<pre> jQuery('.ratio').aspectRatio(); </pre>

###Default setting for the plug-in:
<pre>
.aspectRatio(
  brakepoint : {
    lg : 1199,
    md : 991,
    sm : 767,
    xs : 543
  }
);
</pre>
Object. Brake points for responsive grid ratio, similar for bootstrap grid;

<pre>.aspectRatio(overflow : false);</pre>
Boolean. Overflow or not, for the container object if contents is higher than the ratio height;

<pre>.aspectRatio(transition: true);</pre>
Boolean. Use or not to use a transition animation; 

<pre>.aspectRatio(transitionSpeed: 1);</pre>
Number. Transition speed in seconds (css transition);

<pre>.aspectRatio(debug: false);</pre>
Boolean. Show border for container and children objects and log height information in console on window.resize;

<pre>.aspectRatio(addClass : 'aspectRatio');</pre>
String. Default name for the plug-in object class (mostly used for css effects);
