# Camera Controller

A simple third person camera controller for Unity

## Features

* Collides with the scenery
* Limited camera pitch
* Can target any object in the scene
* Can be be controlled by any input axis (mouse and/or joystick)

## Inspector 

* Target (Transform) : Object aimed by the camera
* Distance : Distance to keep between the camera and Target
* Lerp Speed : Lerp factor, when the distance changes because the camera hit something
 
** Ray Trace (Collision Parameters) **

 * Thickness : Ray thickness
 * Collision Mask : Layers the camera collides with

** Pitch Limits **

* Minimum : Minimum pitch angle, in the range [-90, Maximum]
* Maximum : Maximum pitch angle, in the range [Minimum, 90]

** Input Axes **

Configure here the two axes used to control the camera vertically and horizontally.
Each axis takes the following properties :

* Name : The name of the input axis (refers to an axis set with the input manager)
* Sensitivity : Axis sensitivity. Can be smaller than zero to invert the axis

** Center Camera **

This button on the inspector moves the camera inside the editor to its start location.