# Blender-Parametrized-Rendering
A project for rendering different 3D models using different camera, lighting and angular parameters ( where to place them ).

### How to Run

1. Firstly install <a href="https://www.blender.org/download/">blender</a> on your PC.
2. Now copy the `import_sketchup.py` file provided in the project to the location where blender saves it's python import scripts. In windows the scripts are usually located in `C:\Program Files\Blender Foundation\Blender\[VERSION]\python\lib` folder.
3. Now open the `example.blend` file. 
4. Go to line `17` and update the `path` to the path of the `para_camera.txt` file. `para_camera.txt` is the file where you define the `yaw` , `pitch`, `roll` parameters. For understanding watch <a href="https://www.youtube.com/watch?v=pQ24NtnaLl8">this</a>.
5. Go to line `18` and update the path to the `path file` which contains the `source(models)` and `destination(rendered images)` folder.
6. Now run the script.
