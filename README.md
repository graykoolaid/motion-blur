motion-blur
===========
Looks like its working, need to test spinning objects

Sample uses
  W
A S D
to move around at ground level

Q   E
to change height

This is done with 4 total passes:
Calculate light shadow map (depth)
Draw the scene including the shadowmap
Get the depth of the whole scene (velocity map)
Blur it
