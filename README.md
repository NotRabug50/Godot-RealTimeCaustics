# Godot - (RealTime-ish) Caustics
![](https://img.shields.io/badge/LICENSE-MIT-blue?style=for-the-badge&logo=godotengine)

This is a demo/tutorial showcasing/explaining a way to add cool Caustics effects to your Godot project.

## Disclaimer
The **original** shader code was written by Alex Ameye ([@alexanderameye](https://twitter.com/alexanderameye)). The original article can be found here:  [Rendering realtime caustics](https://alexanderameye.github.io/notes/realtime-caustics/). I merely take credit for the porting of his shader to GLSL and Godot.

## Done / To-Do
* [X] Reconstructing world position from depth
* [X] Bounding Box Mask (caustics only visible inside the box)
* [X] Caustics Mapping over World UV
    * [X] changes with light direction
* [X] Scaling and movement/panning
* [X] Multiple overlaped caustics textures
* [X] Chromatic aberration
* [X] Luminance fade
* [X] Edge fade
* [X] "Underwater camera" -> caustics are being shown when camera is inside the caustics volume

## Showcase
https://user-images.githubusercontent.com/38077837/168200274-83b08559-283a-4e27-889c-390fd504ba43.mp4

https://user-images.githubusercontent.com/38077837/168200293-6cdad355-ee75-4bd8-820f-1db5c0d72f54.mp4


