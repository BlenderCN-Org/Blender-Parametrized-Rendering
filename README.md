# Blender-Parametrized-Rendering
A project for rendering different 3D models using different camera, lighting and angular parameters ( where to place them ).

### How to Run

1. Firstly install <a href="https://www.blender.org/download/">blender</a> on your PC.
2. Now copy the `import_sketchup.py` file provided in the project to the location where blender saves it's python import scripts. In windows the scripts are usually located in `C:\Program Files\Blender Foundation\Blender\[VERSION]\python\lib` folder.
3. Now open the `example.blend` file. 
4. Go to line `17` and update the `path` to the path of the `para_camera.txt` file. `para_camera.txt` is the file where you define the `yaw` , `pitch`, `roll` parameters. For understanding watch <a href="https://www.youtube.com/watch?v=pQ24NtnaLl8">this</a>.
5. Go to line `18` and update the path to the `path file` which contains the `source(models)` and `destination(rendered images)` folder.
6. Now run the script.


## License
```
Copyright © 2018 Muazzam Ali

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

