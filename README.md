# js-1K-raytracer
This repo is an attempt to create most efficient raytracer with most features and source size under 1024 bytes but without WebGL and any external resources. It was made specially for [js1k](http://js1k.com/2017-magic/) contest.

### Raytracer details:
* Language: javascript (es6)
* Compressed source size: 1024 bytes
* No any external data, no any external libraries
* No WebGL, only software rendering

### List of features
1. multiple spheres with own positions, color and sizes
2. spheres final color are combined from diffuse, reflection and specular colors
3. textured floor - tiled carpet (procedure generated)
4. floor has glossy reflections of the world
5. sky is textured with gradient and 'stars'
6. soft shadows on floor and spheres
7. depth of field is also present

It works with shim from js1k, incudes presetted canvas, so my raytracer for contest is not self-contained html page. It contains only js code, without any html. Size of self-contained html with all presetted data is 1121 bytes. This repo contains pure js and self-contained versions, both full size and minimized.

At this moment (January 2017) it works much faster in firefox, than on chrome.

[You can see online preview here](http://js1k.com/2017-magic/demo/2648)
