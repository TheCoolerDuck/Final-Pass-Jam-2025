# World Dither Effect

**Confirmed working with Unity version `2022.3.30f1`**  
No known version issues, but tested specifically on this version.

---

##Contents

C# Scripts

- `Rotate.cs`  
  Rotates the GameObject it’s attached to at a configurable speed. Useful for demo scenes.

- `Shader_Helper_Functions.cs`  
  A collection of helper functions for use in shader-related C# scripts. Feel free to reuse or extend.

- `ViewController.cs`  
  A simple fly-style camera controller script for navigating the display scene.

- `World_Dither.cs`  
  The core effect controller script. Attach this to a GameObject with a `Camera` component.

Shaders

- `World Dither.shader`  
  The main shader file where the dithering effect is implemented.

Scenes

- `World Dither`  
  A minimal demo scene to showcase the dithering effect in action.

---

##How to Use

1. Open the project in Unity `2022.3.30f1`.
2. Open the `World Dither` scene (or create your own).
3. Attach the `World_Dither.cs` script to a GameObject that has a `Camera` component.
4. Play the scene and enjoy the effect!

---
