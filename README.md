# My first three.js app

Diving into the world of javascript and 3D websites I found about three.js which I thought was great at first but after visiting it's website and going through the projects and examples I can see this is the future of the web experience. It has elements of metaverse and virtual reality built into it. Also the abstract visuals that can be made are just mesmerising and out of this world. It's hard for me to wrap my head around how this apps are built and what does it really take to build one such on my own. After building the starter I can see there's a lot I need to know to begin but to make something and test out this amazing piece of code, it really doesn't take any more than knowing scratch and having the gut's to mess around with the code and see what comes out.

# Rotating Cube

1. Just copy the three.js file to js/three.js
2. Link the three.js script along with the html and add your own script
3. Three things needed in order to display anything (Is this the reason for the three.js name?)
    - Scene
    - Camera
    - Renderer

Camera: PerspectiveCamera

PerspectiveCamera(fieldOfView[degrees], aspectRatio[width/height], near, far[clippingPlane])

Renderer: WebGLRenderer

> Note: We also have to set the size we want to render the app and add renderer to the HTML document. ( Best to use the width and height of the area we want the app to fill ). We can set the resolution to be half while keeping the size same.


4. Adding the Cube/Mesh
    - Create geometry which will contain the mesh.
    - Create material for the mesh ( just to give it some color ).
    - Create an actual mesh with the geometry and material which we can insert into our scene.
    - Add the mesh to our scene. By default it gets added at (0,0,0).
    - To avoid camera and mesh to be inside each other we shift the camera up the z axis.

5. Render / Animate loop
    - Render the scene and camera




