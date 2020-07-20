# Unity XR Remoting Package

## Overview
This is a backup of the Unity XR Remoting package that used to be hosted at https://staging-packages.unity.com. It was sourced from
https://unity.bintray.com/unity-staging/ but was archived here for the specific use of LinkedIn Learning users working on the course "Unity: AR Visualization 01 Basic Concepts" (https://www.linkedin.com/learning/unity-ar-visualization-01-basic-concepts/)

## Usage
To use this Unity package, please open the "Packages/manifest.json" file.
Find the line
```
"com.unity.xr.remoting": "0.0.1-preview.10"
```
and replace it with
```
"com.unity.xr.remoting": "https://github.com/collectivemass/com.unity.xr.remoting-0.0.1-preview.10.git"
```

If you have the JSON node
```
"registry" : "https://staging-packages.unity.com"
```
present in your manifest, remove it completely. 

Your manifest should look something like:
```
{
  "dependencies": {
    "com.unity.collab-proxy": "1.2.16",
    "com.unity.mobile.android-logcat": "0.1.5-preview",
    "com.unity.package-manager-ui": "2.1.2",
    "com.unity.textmeshpro": "2.0.0",
    "com.unity.timeline": "1.0.0",
    "com.unity.xr.arcore": "1.0.0-preview.24",
    "com.unity.xr.arfoundation": "1.1.0-preview.6",
    "com.unity.xr.arkit": "1.0.0-preview.27",
    "com.unity.modules.ai": "1.0.0",
    "com.unity.modules.animation": "1.0.0",
    "com.unity.modules.assetbundle": "1.0.0",
    "com.unity.modules.audio": "1.0.0",
    "com.unity.modules.cloth": "1.0.0",
    "com.unity.modules.director": "1.0.0",
    "com.unity.modules.imageconversion": "1.0.0",
    "com.unity.modules.imgui": "1.0.0",
    "com.unity.modules.jsonserialize": "1.0.0",
    "com.unity.modules.particlesystem": "1.0.0",
    "com.unity.modules.physics": "1.0.0",
    "com.unity.modules.physics2d": "1.0.0",
    "com.unity.modules.screencapture": "1.0.0",
    "com.unity.modules.terrain": "1.0.0",
    "com.unity.modules.terrainphysics": "1.0.0",
    "com.unity.modules.tilemap": "1.0.0",
    "com.unity.modules.ui": "1.0.0",
    "com.unity.modules.uielements": "1.0.0",
    "com.unity.modules.umbra": "1.0.0",
    "com.unity.modules.unityanalytics": "1.0.0",
    "com.unity.modules.unitywebrequest": "1.0.0",
    "com.unity.modules.unitywebrequestassetbundle": "1.0.0",
    "com.unity.modules.unitywebrequestaudio": "1.0.0",
    "com.unity.modules.unitywebrequesttexture": "1.0.0",
    "com.unity.modules.unitywebrequestwww": "1.0.0",
    "com.unity.modules.vehicles": "1.0.0",
    "com.unity.modules.video": "1.0.0",
    "com.unity.modules.vr": "1.0.0",
    "com.unity.modules.wind": "1.0.0",
    "com.unity.modules.xr": "1.0.0",
    "com.unity.xr.remoting": "https://github.com/collectivemass/com.unity.xr.remoting-0.0.1-preview.10.git"
  }
}

```
