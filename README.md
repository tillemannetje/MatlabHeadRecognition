# MatlabHeadRecognition
Matlab Code (*of a top-down head image*) for the recognition of the nose tip, the exact middle of both the ears and the back of the head.

*Using a top-down image of bald head*

I want to acquire the positions (in the image: pixels position/coordinates) of:
- The tip of the nose;
- The exact middle of both the ears.
- The coordinates of the intersection of a perfectly straight line (running from the tip of the nose all the way down to the bottom of the picture) with the back of the head 

I've got the code where the image is converted to a gray and binary image so the outer lines of the head are shown. 

Now I don't know how to generate the straight line and automatically (by code) acquire the coordinates of: the tip of the nose, exact middle of the ears and the intersection of the straight line with the back of the head.


In logical order (I presume) the coding should involve:

- Finding the coordinates of the nose tip.
- Draw a straight line down from the tip of the nose
- Find the coordinates of the exact middle of the ears
