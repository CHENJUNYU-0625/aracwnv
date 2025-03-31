<!DOCTYPE html>
<html>
<head>
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
    <script src="https://cdn.jsdelivr.net/gh/jeromeetienne/ar.js/aframe/build/aframe-ar.min.js"></script>
</head>
<body style="margin: 0; overflow: hidden;">
    <a-scene embedded arjs>
        <!-- AR 標記 (預設 Hiro 標記) -->
        <a-marker preset="hiro">
            <a-entity 
                gltf-model="https://example.com/tinkywinky.glb" 
                scale="0.5 0.5 0.5"
                position="0 0 0"
                rotation="0 180 0">
            </a-entity>
        </a-marker>
        <a-entity camera></a-entity>
    </a-scene>
</body>
</html>
