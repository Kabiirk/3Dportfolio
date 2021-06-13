# **3D Portfolio w/ Three.js**

A 3D Website made using [Three.js](https://threejs.org/) - a cross-browser JavaScript library and application programming interface used to create and display animated 3D computer graphics in a web browser using WebGL.

## Contents
* Try Running it yourself !

### Try Running it yourself
* **Start a WebServer**
    <br>Chrome and other modern browsers have implemented security restrictions for **Cross Origin Requests (CORS)**, which means that we cannot load anything through ```file:///``` , we need to use ```http://``` protocol at all times, even locally - due to Same Origin policies. Therefore, a webserver is to be mounted to run the project, otherwise the following error occurs (on Google Chrome) while loading assets from local storage :

    > Access to ```asset``` at ```'url'``` from origin 'null' has been blocked by CORS policy: Cross origin requests are only supported for protocol schemes: http, data, chrome, chrome-extension, chrome-untrusted, https.</br>

* **Run index.html**
    <br>This website only uses the Three.js and Three.js - OrbitControls CDNs. So Installation of packages (npm etc.) isn't required. All that is needed to be done is to clone the repo & run [index.html](https://github.com/Kabiirk/3Dportfolio/blob/main/index.html) on a live webserver. </br>

**NOTE:** Although no packages are installed, it is always preffered to do so (or using both) since CDNs can be updated frequently and may break some stuff. (unlike package instllations where you can control which version you use.)