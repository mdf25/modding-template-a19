# RESOURCES
This folder should only be used if you are using Unity to add new assets. If not, you can safely remove it.

This is where you need to put .unity3d files that you create yourself from Unity assets.

## What assets can be included in unity3d files?
The following assets can be included and referenced from within a modlet's Configs:
- Prefabs
- Textures and texture arrays
- Sounds
- Materials
- Particles
- Animations and controllers

Note that scripts will NOT work in unity3d files, even if you have applied them to a model or something as part of a prefab. 

If you need to attach your own script to an object, you will need to use DNT to inject the script on object creation/loading.

## How to reference an asset path
Let's say you created a cube in Unity called 'MyCube' and you exported it as a prefab into a unity3d file called 'Blocks.unity3d'.

- Place your .unity3d file in this folder.
- In the XML, your asset path is: ```#@modfolder:Resources/Blocks.unity3d?MyCube.prefab```

Sounds and materials can be accessed in the same way.
```
#@modfolder:Resources/{assetBundleName}.unity3d?{assetName}
```