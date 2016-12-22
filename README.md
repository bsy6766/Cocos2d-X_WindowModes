# Cocos2d-X_WindowModes
Added Windowed Fullscreen on Cocos2d-x 3.14 with new GLFW(3.2.1+). 
## What is this?
This is a simple modification on Cocos2d-X desktop window creation. It allows you to create/toggle window with all 3 window modes (Windowed, Fullscreen and Windowed Fullscreen (aka Borderless Fullscreen)).<br>
Cocos2d-X 3.14 already supports Windowed mode and Fullscreen mode but I added Windowed Fullscreen.
## Why?
I wanted to make my game to support all 3 window modes and be able to switch between in runtime, which means no need to close and restart game everytime you change window mode.
## Support
Currently it only supports Windows only.<br>
Usage is same as before, it's very straight forward, read header and you will figure it out right away.
## How to use
Copy and past cocos2d folder in repo folder to your cocos2d game folder and overwrite existing glfw lib and GLViewImpl.
