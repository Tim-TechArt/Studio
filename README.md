# Studio
_My little Tech-Art VFX Studio_
## Introduction
This project is set up from a blank template. I'm building everything from the ground up to better understand every aspect of how a game works in Unreal Engine 5.<br> 
However, I'm not a 3D modeler nor an animator, so for these parts, I will use free assets.<br> 
At some point, I'll also be shifting parts of the Blueprint logic into C++ to gain a deeper understanding of how this aspect operates. <br> 
I'm doing this project in my spare time so it will probably be a bit slow :) <br>
<br> 
This will end up with an attack effect that will be triggered in-game.

## Progress

### Currently working on:
* Animation montage so I can stitch together animations for an attack effect.

### Documented progress
_This will work as a journal of my progress._

#### Animation Blueprint
* Setup basic Ground Locomotion
* Added Blend space for running/walking in different directions 
* Setup basic Jump Locomotion
* Added "Default Slot" so Animation Montages will work
* Added _Layered blend per bone_ for slot "Upper Body" 

#### BP_Player
* Initialization of Enhanced Input-mapping
* Logic for Enhanced Input-mapping
* Player mesh
* Spring arm with attached camera
* Some logic to make it work better with third-person view
* Made running speed analog when using gamepad left trigger

#### Setup Enhanced Input-mapping
* Input Actions for Movement, Run, Jump and Attack
* Input Mapping Context
* Added support for gamepad

#### VFX
* Tinkered with _material functions_ for varius Chromatic Aberration effects
* Made _material function_ for doing _Iridescence_
* Made _Snow_ materia with sparkling sparks
* Tons of other bits and pieces I hopefully will have use for later on :D


## Controllers

### Keyboard + Mouse

* Move: WASD
* Look: Mouse
* Attack: Left Mouse Button
* Run: Shift
* Jump: Space Bar


### GamePad

* Move: Left Stick
* Look: Right Stick
* Attack: A
* Run: X
* Jump: B
