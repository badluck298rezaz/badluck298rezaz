### Hi there 👋
// 1) Create a Renderer for the context you would like to render to.
//    You can use either the WebGLRenderer, CanvasRenderer or SVGRenderer.
var renderer = new FSS.CanvasRenderer();

// 2) Add the Renderer's element to the DOM:
var container = document.getElementById('container');
container.appendChild(renderer.element);

// 3) Create a Scene:
var scene = new FSS.Scene();

// 4) Create some Geometry & a Material, pass them to a Mesh constructor, and add the Mesh to the Scene:
var geometry = new FSS.Plane(200, 100, 4, 2);
var material = new FSS.Material('#444444', '#FFFFFF');
var mesh = new FSS.Mesh(geometry, material);
scene.add(mesh);

// 5) Create and add a Light to the Scene:
var light = new FSS.Light('#FF0000', '#0000FF');
scene.add(light);

// 6) Finally, render the Scene:
renderer.render(scene);

<!--
**badluck298rezaz/badluck298rezaz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
