# human

Trying to model human procedurally in 3D. Face first.
Want an iteratively refinable model suspectible to animation / deformation.

## Resources

 - [three.js examples bump map skin](https://threejs.org/examples/?q=materials#webgl_materials_bumpmap_skin)
 - [Human face closeup (Angelina Jolie)](http://yesofcorsa.com/wp-content/uploads/2015/07/4801_angelina_jolie.jpg)
 - [Facial Muscles @ Wikipedia](https://en.wikipedia.org/wiki/Facial_muscles)
 - [Human skull](https://cdnb3.artstation.com/p/assets/images/images/000/227/915/large/ivan-mityaev-skull-front.jpg?1443931826)


## Setup

To get an interactive development environment run:

    lein figwheel

and open your browser at [localhost:3449](http://localhost:3449/).
This will auto compile and send all changes to the browser without the
need to reload. After the compilation process is complete, you will
get a Browser Connected REPL. An easy way to try it is:

    (js/alert "Am I connected?")

and you should see an alert in the browser window.

To clean all compiled files:

    lein clean

To create a production build run:

    lein do clean, cljsbuild once min

And open your browser in `resources/public/index.html`. You will not
get live reloading, nor a REPL. 

## License

Copyright © 2014 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
