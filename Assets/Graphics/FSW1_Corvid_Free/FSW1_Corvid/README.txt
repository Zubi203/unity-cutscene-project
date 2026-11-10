FSW-1 Corvid - forward-swept-wing fighter
by @GodTrigger0  ·  https://cuigames.itch.io
Free ($0 or donate).

An original forward-swept-wing fighter in an arcade flight-game style.

CONTENTS
  FSW1_Corvid.glb   FSW1_Corvid.fbx   FSW1_Corvid.blend   textures/
  README.txt, LICENSE.txt

FORMATS
- .glb    glTF 2.0 binary, PBR materials and textures embedded, 6 named animation clips.
- .fbx    binary FBX 7.4, textures embedded. All 6 clips are laid out one after another
          on a single timeline (table below).
- .blend  editable Blender source, textures packed inside the file
          (textures/ holds 4096x4096 PNG copies: BaseColor, ORM, Normal, Emissive).
- 119,737 triangles, 80 mesh parts, 23 materials.
  About 22.7 m long, 15.8 m wingspan. Z-up in Blender, Y-up in glTF.

ANIMATIONS (6 clips, 24 fps, 60 frames / about 2.5 s each)
  Clip            FBX timeline frames
  GearRetract       0 -  59   landing gear and gear doors retract
  CanopyOpen       60 - 119   canopy opens on its jacks
  ControlSurfaces 120 - 179   canards, flaperons, slats and rudders sweep
  WeaponBayOpen   180 - 239   bay doors open, missiles extend
  Afterburner     240 - 299   nozzles and afterburner plumes
  CannonFire      300 - 359   gun port door, barrels and muzzle flash
In the GLB every clip is a separate named animation.
In Blender: open the Nonlinear Animation editor. Each clip is an NLA track with the same
name, all muted. Unmute the tracks of the clip you want, then press Space to play.

BLENDER VERSION
The .blend file was saved with Blender 5.0. Use Blender 5.0 or newer to open it.
The .glb / .fbx files work in any glTF 2.0 / FBX importer.

KNOWN LIMITS
- The cannon flash light (Gun_Flash_Light) and the afterburner glow lights exist only in
  the .blend. The GLB / FBX keep the emissive muzzle-flash and plume meshes, but no lights.
- There is slight interpenetration at some hinges (canopy and control surfaces) while
  they move.
- Not tested inside a specific game engine (Unity / Unreal / Godot should import the glTF
  or FBX, but materials, mipmaps and animation controllers are your responsibility).
- Fictional design, not based on, affiliated with or endorsed by any real aircraft
  manufacturer.
- Created with AI-assisted tools and refined by the creator.
