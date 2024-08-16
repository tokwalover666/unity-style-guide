# Unity Style Guide
My must follow rules in setting up my projects in unity.

## General Guidelines

- use `[SerializedField]` for accessing private variables within unity editor but not from other scripts
- use public variables when it is needed to access by multiple scripts
- be consistent in naming conventions for clarity and ease of project navigation

## Project Structure
<pre>
Assets/
    _Scenes/
    Audios/
    Materials/
    Models/
    Scripts/
    Shader/
</pre>

## Naming Conventions

  ***Folders***
- Folder name should be in PascalCase(e.g.,  `Scenes`, `Materials`)


***Scripts and Variables***
  
| Category | Naming Style | Example |
-----------| -------------| --------|
| Scripts | PascalCase | `PlayerController.cs` |
| Public Variables | PascalCase | `PlayerHealth` |
| Private Variables | camelCase | `movementSpeed` |
| Methods | PascalCase | `PlayAudio()` |



***Assets***
  
| File Type | Prefix | Suffix | Example | 
------------|--------|--------|---------|
| Materials | MAT_ | | `MAT_Skin` |
| Prefabs | PREF_ | | `PREF_Player` |
| Sprites | SPR_ | | `SPR_Enemy.png` |
| Textures | TEX_ | _N, _AO, _D | `TEX_Skin_N.png`, `TEX_Skin_AO.png` |
| Audio Clips | SFX_ |  | `SFX_Explosion.wav` |
| UI Elements | UI_ |  | `UI_StartButton.png` |

  ***Scenes***
  
- Scene names must follow PascalCase(e.g., `MainMenu`, `Level1`, `GameOverScreen`)
