# Newskin-videojs-v8

Newskin skin videojs v8
<img src="https://raw.githubusercontent.com/FutileZero/Newskin-videojs-v8/refs/heads/main/Newskin.png">
### Quick Start

```
html
<link href="https://unpkg.com/video.js@8.23.7/dist/video-js.min.css" rel="stylesheet">
<script src="https://unpkg.com/video.js@8.23.7/dist/video.min.js"></script>
<script src="Newskin.js"></script>

<video id="player" class="video-js Newskin"></video>
<script>
var Player = videojs("player", { 
"controls": true, 
"autoplay": false, 
"preload": "auto" ,
"poster": "http://vjs.zencdn.net/v/oceans.png",
"width": 960,
"height": 400,
sources: [
{ src: 'https://vjs.zencdn.net/v/oceans.mp4', type: 'video/mp4'},
{ src: 'https://vjs.zencdn.net/v/oceans.webm', type: 'video/webm'},
{ src: 'https://vjs.zencdn.net/v/oceans.ogv', type: 'video/ogg'}
],
});
</script>
```
