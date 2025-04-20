# World Dither Effect

**Confirmed working with Unity version `2022.3.30f1`**  
No known version issues, but tested specifically on this version.

---

## Contents

### C# Scripts

- `Rotate.cs`  
  Rotates the GameObject it’s attached to at a configurable speed. Primarily for demonstration purposes.

- `Shader_Helper_Functions.cs`  
  A set of utility functions for use in shader-related C# scripts.

- `ViewController.cs`  
  A basic fly-style camera controller script for navigating the scene.

- `World_Dither.cs`  
  The main effect script. Attach this to a GameObject with a `Camera` component to enable the dithering effect.

### Shaders

- `World Dither.shader`  
  Contains the core implementation of the dithering effect.

### Scenes

- `World Dither`  
  A minimal demonstration scene showcasing the effect.

### Banana Man Folder

- A sample model from the Unity Asset Store:  
  [Banana Man - Unity Asset Store](https://assetstore.unity.com/packages/3d/characters/humanoids/banana-man-196830)

---

## How to Use

1. Open the project in Unity `2022.3.30f1`.
2. Open the `World Dither` scene (or create a new one).
3. Attach the `World_Dither.cs` script to a GameObject that has a `Camera` component.
4. Enter Play mode to see the effect in action.
