# Studio
_My little Tech-Art VFX Studio_
## Introduction
This project is set up from a blank template. I'm building everything from the ground up to better understand every aspect of how a game works in Unreal Engine 5.<br> 
However, I'm not a 3D modeler nor an animator, so for these parts, I will use free assets. And _disclaimer_: there will be some placeholders I'm using while experimenting with things that I haven't done 100% myself.<br> 
<br> 
At some point, I'll also be shifting parts of the Blueprint logic into C++ to gain a deeper understanding of how this aspect operates. <br> 
I'm doing this project in my spare time so it will probably be a bit slow :) <br>
<br> 
This will _hopefully_ end up with an attack effect that will be triggered in-game.

## Progress

### Currently working on:
* Moving animation BP logic to thread safe instances for optimization
* Moving animation BP to Linked Anim Layers
* Animation montage so I can stitch together animations for an attack effect.


### Needs more work
* Jumping animation is wacked 

### Documented progress
_This will work as a journal of my progress._

#### Animation Blueprint
* Setup basic _Ground Locomotion_
* Added _Blend space_ for running/walking in different directions 
* Setup basic _Jump Locomotion_
* Added _Default Slot_ so Animation Montages will work
* Added _Layered blend per bone_ for slot "Upper Body" 

#### BP_Player
* Initialization of Enhanced Input-mapping
* Logic for Enhanced Input-mapping
* Added Player mesh
* Spring arm with attached camera
* Some camera logic to make it work better with third-person view
* Made running speed analog when using gamepad left trigger

#### Setup Enhanced Input-mapping
* Input Actions for Movement, Run, Jump and Attack
* Input Mapping Context
* Added support for gamepad

#### VFX
_Gif's will arrive later on_
* Tinkered with _material functions_ for varius Chromatic Aberration effects
* Made _material function_ for doing _Iridescence_
* Made _Snow_ material with sparkling sparks
  - Packed normals, AO and roughness in same texture
* Tons of other bits and pieces I hopefully will have use for later on :D


## Controllers

### Keyboard + Mouse

* Move: WASD
* Look: Mouse
* Attack: 1
* Run: Shift
* Jump: Space Bar


### GamePad xBox

* Move: Left Stick
* Look: Right Stick
* Attack: A
* Run: LT
* Jump: B
