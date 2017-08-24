# particles.js
A modification of particles.js to use custom icon images are particles.

### Usage
Simpy update the array of image source in app.js and you will see images moving like particles

**index.html**
```html
<div id="particles-js"></div>

<script src="particles.js"></script>
```

**app.js**
```javascript
/*Image source array*/
let img_src = ['assets/images/001-interface.png', 'assets/images/002-share.png', 'assets/images/003-key.png','assets/images/004-front.png','assets/images/005-reception.png','assets/images/006-bed.png','assets/images/007-hotel.png','assets/images/008-room.png','assets/images/009-like.png'];


/* particlesJS.load(@dom-id, @path-json, @callback (optional)); */
particlesJS.load('particles-js', 'assets/particles.json', function() {
  console.log('callback - particles.js config loaded');
});
```