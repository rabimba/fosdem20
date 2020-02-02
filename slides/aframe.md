
<!-- .slide: data-background="resources/textures/background-radial.jpeg" -->

<div class="captioned-image-row">
  <div>
    <img class="plain" data-src="media/img/aframe-logo-rendered.png">
    <i>Frameworks:<br> AFrame</i>
  </div>
</div>

------

## Hello World

<!-- .slide: data-background="media/img/aframe.jpg" data-transition="fade-in slide-out" -->

```html
<html>
  <script src="https://aframe.io/releases/0.5.0/aframe.min.js"></script>
  <a-scene>
    <a-box color="#4CC3D9" position="-1 0.5 -3" rotation="0 45 0"></a-box>
    <a-cylinder color="#FFC65D" position="1 0.75 -3" radius="0.5" height="1.5"></a-cylinder>
    <a-sphere color="#EF2D5E" position="0 1.25 -5" radius="1.25"></a-sphere>
    <a-plane color="#7BC8A4" position="0 0 -4" rotation="-90 0 0" width="4" height="4"></a-plane>
    <a-sky color="#ECECEC"></a-sky>
  </a-scene>
</html>
```
<!-- .element: class="stretch" style="background: rgba(32, 32, 32, 0.5);" -->

<!-- NOTES -->
- Basic 3D primitives with Custom Elements
- Readable: HTML arguably most accessible language in computing
- Encapsulated: copy-and-paste HTML anywhere else and still work, no state or variables
- Quickly look at a live example...

------

<!-- .slide: data-background="media/img/aframe.jpg" -->
<div style="background: rgba(32, 32, 32, 0.5);">
    <h2>Works With Everything</h1>

  <div class="captioned-image-row">
    <div>
      <img class="plain" data-src="media/img/d3.png">
      <i>d3.js</i>
    </div>
    <div>
      <img class="plain" data-src="media/img/vue.png">
      <i>Vue.js</i>
    </div>
    <div>
      <img class="plain" data-src="media/img/react.png">
      <i>React</i>
    </div>
    <div>
      <img class="plain" data-src="media/img/redux.png">
      <i>Redux</i>
    </div>
    <div>
      <img class="plain" data-src="media/img/jquery.png">
      <i>jQuery</i>
    </div>
    <div>
      <img class="plain" data-src="media/img/angular.png">
      <i>Angular</i>
    </div>
  </div>
</div>

<!-- NOTES -->

- Based on HTML, compatible with all existing libraries/frameworks
- Good reason to have HTML as an intermediary layer between WebGL/three.js
- All tools were on top of the notion of HTML
- Under the hood, A-Frame is an extensible, declarative framework for three.js...

------

<!-- .slide: data-background="media/img/header.png" -->

# Community

https://aframe.io/blog/

---

<!-- .slide: data-background="media/img/apainter.gif" -->

# Art - *A-Painter*

@mozillavr

---

<!-- .slide: data-background="media/img/syria.gif" -->

# Journalism - *Fear of the Sky*

Amnesty International UK

---

<!-- .slide: data-background="media/img/adit.gif" -->

# Data Visualization - *Adit*

@datatitian


