# LocalPhotoSphere

A single static html page to show Photo Spheres

LocalPhotoSphere is a single html static file that allows you to specify a photosphere file and it display it in your browser. Nothing is uploaded to any server. Everything is kept locally in your browser. This works offline if you save the page first.

Photospheres can be shot using Google photos apps such as http://www.appbrain.com/app/com.google.android.GoogleCamera or the default camera from your phone manufacturer, if it has the option. More on photospheres: https://www.lifewire.com/what-is-android-photo-sphere-1616136.

There's not many bells or whistles but there's no external dependencies at all either.
The following external code is directly embedded in the main file:
- Threejs - https://threejs.org/ - a cross-browser JavaScript library and Application Programming Interface used to create and display animated 3D computer graphics in a web browser. Three.js uses WebGL.
- Photo-Sphere-Viewer - https://github.com/JeremyHeleine/Photo-Sphere-Viewer - A JavaScript library to display Photo Sphere panoramas.

Pull requests to improve or add functionalities are welcome.


# Minimalism
The entire code is 78 'lines' of code but because of the embedded libraries, it still weights 475KB.
