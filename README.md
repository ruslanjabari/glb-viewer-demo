# glb-viewer
 
https://code4fukui.github.io/glb-viewer/


## glb2gltf

```
npm i
./node_modules/gltf-pipeline/bin/gltf-pipeline.js -i fn.glb -o fn.gltf
```

## gltf2glb

```
./node_modules/gltf-pipeline/bin/gltf-pipeline.js -i fn.gltf -o fn.glb
```

## extract texture images from gltf

```
deno run -A extractImageFromGLTF.js fn.gltf
```

## remake gltf with texture images

```
deno run -A remakeGLTF.js fn.gltf fn-texture.jpg
```

# glb-viewer-demo
# glb-viewer-demo
