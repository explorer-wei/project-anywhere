# Project Anywhere

## Introduction

***Project Anywhere*** is an essential component of [Mirror Worlds](https://icat.vt.edu/projects/misc/mirror-worlds.html), meant to provide the capability of projecting an image from the virtual world into the real world. It can either serve as a way to provide notifications between the two worlds or as a portal to share interactive information between users in the virtual and those in the physical.

![](/Documents/project-anywhere-mirror-worlds.png)

Our idea was to take an LCD projector and combine it with a rotating mirror. The rotation of the mirror would allow the image being projected to be displayed on multiple surfaces in a given room. This approach has been named Project Anywhere.

## Prototype

The prototype system uses a user interface designed in Unity3D to serve as a simple and easy to use program for the virtual user to select a position in a room to project a laser pointer or real projector image at. This prototype however specifically uses a laser pointer for its projections. The system rotates a mirror at corresponding angles in order to reflect the light beam of the laser pointer to a desired location.

![prototype system](/Documents/project-anywhere-prototype.png)

As shown in the photo above, the hardware part consist of the follow materials and items: two Arduino Uno boards (the one that controls the motors is shown and the other one that is connected to the computer which runs the Unity3D interface is not shown), two Servo motors (torque of 16.6/20.8 oz-in), a hand size plane mirror, a rotation harness to hold the mirror (built using wooden dowels, metal, and tape), a laser pointer, and a Styrofoam laser pointer holder.

![prototype system](/Documents/project-anywhere-prototype-ui.png)

The Unity3D user interface purpose is to serve as an easy to use, simple interface that allows the virtual user to select a position in the room to project an image. 
-	Bullseye-Target Selector: This button is clicked by the user to specify the desired location of new projection
-	Send: This button sends the calculated angles that would rotate the motors horizontally and vertically to adjust the mirror reflected image to project the newly desired location
-	Reset: This button allows the user to reset the values for the angle calculations back to the initial position
-	“Angle 1”: This parameter shows the angle calculation of the rotation in the horizontal direction
-	“Angle 2”: This parameter shows the angle calculation of the rotation in the vertical direction

## Acknowledge
Thanks to Ekta Bindlish, Stephanie Mencia, and Eric Refour for working with me in "ECE 5564: Wearable and Ubiquitous Computing" @ Virginia Tech 2015 Spring.
