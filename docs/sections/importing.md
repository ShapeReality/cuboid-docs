# Importing assets

## Install the Cuboid Unity Plugin

Get the Cuboid Unity Plugin at: 

[github.com/ShapeReality/com.cuboid.unity-plugin/releases](https://github.com/ShapeReality/com.cuboid.unity-plugin/releases)

Download the latest `.unitypackage` file. Once it's downloaded, drag it into the `Project` window in your Unity project or a new empty Unity project. 

## Basic Usage

1. In the Project window, right click and select `Cuboid > Create Asset Collection` and name it to your liking. 

2. Then, in the Top Menu Bar, go to `Cuboid > Asset Collections`.

3. Select the newly created Asset Collection in the Asset Collections window. 

4. Drag your Prefabs and imported 3D models into the Asset Collections window. These will now be added to the Asset Collection.

5. Click build and select the desired target location on your disk. Your Asset Collection `.zip` file will now be built. 

6. Once built, move the `.zip` file onto the headset by plugging it into the computer (on macOS use Android File Transfer) and putting the `zip` file into the `data/com.ShapeReality.Cuboid/Assets` folder. 

!!!Note
    You can also select multiple Asset Collections at the same time by holding shift or command. Now you can bulk export you Asset Collections

!!!Note
    If your object shows up with pink (missing) shaders, please contact us at [contact@shapereality.io](mailto:contact@shapereality.io). 

## Quickly converting an entire folder of assets

Select a folder containing the imported 3D models and Prefabs, right click and select `Cuboid > Convert to Asset Collection`. 

A new Asset Collection will be created containing all imported 3D models and Prefabs inside that Folder. 

!!!Note
    If you have multiple folders selected, it will bulk convert each of these folders into a separate Asset Collection. 

## Limitations

!!!Warning
    Make sure the Unity version matches the Unity version of the application. 

!!!Warning
    The app is built on the URP (Universal Rendering Pipeline) and supports only assets that are built with compatible shaders. 