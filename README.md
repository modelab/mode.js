# mode.js
<a href="http://modelab.is/" target="_blank"><img src="/img/logo/MODELAB_Logo-Horizontal.png" alt="logo" width= "300"/></a>

<a href="https://github.com/modelab/mode.js">mode.js</a> an open-sourced project aimed at creating web-based tools for computational design. Our studio is dedicated to building custom parametric models for the web - and this our repository for sharing utility functions and example files.

<a href="http://modelab.is/news/" target="_blank">Mode Lab </a> - main site

<a href="http://executable.io/" target="_blank">Mode Lab tools</a> - sandbox of design tools.

### Usage
Download the [library](https://raw.githubusercontent.com/modelab/mode.js/master/build/mode.js) and include it in your html.

```html
<script src="js/mode.js"></script>
```

Many of the functions build off of existing libraries. Below is an example using objects from <a href="https://github.com/mrdoob/three.js" target="_blank">THREE.js</a>.  This is a code snippet from the <a href="http://executable.io/html/mode-js/examples/boundingBox_planeIntersect.html" target="_blank">contoured bunny</a> example.
```javascript
//define bounding box by plane or normal vector
//arguments are THREE.Geometry and THREE.Plane/THREE.Vector3
var bb = new MODE.boundingBox(mesh.geometry, normalVector); 
```

### Examples
Example files are in the <a href="https://github.com/modelab/mode.js/tree/master/examples" target="_blank">examples</a> directory for this repo.  Additional demos are posted periodically on <a href="http://executable.io/" target="_blank">http://executable.io/</a>.

<li><a href="http://executable.io/2016/03/25/mode-js-bounding-box-and-plane-intersection/" target="_blank">Example_01</a></li>

### Documentation
In-progress documentation is currently stored <a href="http://executable.io/html/mode-js/doc/MODE.html" target="_blank">here</a>.

### Dependencies
Many of the utility functions are dependent on some of our favorite libraries:
##### <a href="http://threejs.org/" target="_blank">THREE.js</a> - we use THREE for 3D interaction and GPU operations
Three.js is a cross-browser JavaScript library/API used to create and display animated 3D computer graphics in a web browser. Three.js uses WebGL. The source code is hosted in a repository on GitHub.
##### <a href="https://d3js.org/" target="_blank">D3.js</a> - we use D3 for 2D vector graphics and data management/interaction
D3.js is a JavaScript library for manipulating documents based on data. D3 helps you bring data to life using HTML, SVG, and CSS. D3’s emphasis on web standards gives you the full capabilities of modern browsers without tying yourself to a proprietary framework, combining powerful visualization components and a data-driven approach to DOM manipulation.

### Licensing
All mode.js content is protected under the <a href="https://opensource.org/licenses/MIT" target="_blank">MIT License</a>.
