# unity_overdraw-visualizer

![Screenshot](overdraw_visualizer_example.PNG)

Overdraw visualization tool for unity.

Attaching the script to a camera, will render the view with a replacement shader - to produce an "overdraw texture".
This texture is then sampled by a compute shader, for visualizing overdraw ranges - and calculating average/maximum overdraw.


To Do:
- Implement GUI settings
- Implement replacement shader for opaque and transparent shaders (currently using all transparent)

lerpingfx@gmail.com
