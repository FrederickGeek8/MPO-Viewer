MPO-Viewer
==========

New age MPO viewer! (optimized for 3DS)

Notes
=====

If 3D offset does not appear right (image wiggle doesnt look 3D), the offset (cropping from left and right) can be modified with the following CSS:

line 63 (subtracted from 640): <code>clip: rect(0px,550px,auto,0px);</code>

and

line 67: <code>margin-left:-90px;</code>
