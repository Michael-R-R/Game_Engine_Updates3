# Game_Engine_Updates3

### *All further updats will be posted to my website: https://codecreatehub.wordpress.com/ *

Part 3 of my graphics engine updates. Repo for updating and showcasing new features in my graphics engine. Source code remains private. This project is mainly for education purposes. Any graphics engine names are just place holders.

### UPDATE_11:
- UI design overhaul, inspired by my other project: https://github.com/Michael-R-R/GW2_Tool_Hub
- First primitive game object implemented, the cube.
- Redesigned the class for adding game object settings to be more readable and friendly
- Object color picker implemented

![UI_Design](https://user-images.githubusercontent.com/54217603/128939347-bf8d895f-ebba-4c82-94bb-deba6e91a5d8.png)

![First_Blockout](https://user-images.githubusercontent.com/54217603/128942571-8310387c-2e36-4790-bced-baaa7573b162.png)

### UPDATE_12:
- Implemented Bullet physics library into the engine.

![QtGL_NewPhysics](https://user-images.githubusercontent.com/54217603/129428477-14f2849c-6ffb-45c6-8237-785af69c280b.gif)

### UPDATE_13:
- Implemented raycasting, which will allow the use of object selection through clicking.

![QtGL_Raycasting](https://user-images.githubusercontent.com/54217603/129811765-cf7dabbc-442e-4fb6-b9c1-fe71fd632083.gif)

### UPDATE_14:
- Simple object highlighting implemented.

![QtGL_ObjectHighlighting](https://user-images.githubusercontent.com/54217603/130336978-eb09feed-d92f-4dd9-8914-2e2fb4d801d3.gif)

### UPDATE_15:
- Beginning to implement basic lighting methods.
- Each popular lighting type will be implemented and easy to integrate into the scene.

![Basic_Lighting_03](https://user-images.githubusercontent.com/54217603/131050179-c5ba0f41-a9af-42d4-a5c3-44b89637db11.png)

### UPDATE_16:
- Refining the rendering state by implementing batch rendering functionality.
- All meshes are either inserted into their appropriate location in the data structure or the entire structure is re-sorted when needed.
- All meshes that share the same shader will be rendered together in order to save from changing OpenGL states every object.
- Working more on flushing out the Shader Generator in order to make making/updating shaders more easier.
- Began using Excel in order to track functionality better and keep track or important TODOs or fixes. 

![QtGL_BatchRendering](https://user-images.githubusercontent.com/54217603/131872032-48e5a0c5-6e4b-4434-846d-bf2340a5a3c7.gif)

![Excel_Tracking](https://user-images.githubusercontent.com/54217603/131872884-e075b7c3-610b-4271-9c4b-a74736673669.png)

