# Latest changes for the next public release

## Changes
- Updated the watermark again
- Made moss not affect cobwebs
- Small tweaks to translucents with floor noise
- Remove sand in the lower parts of caves (transition starting at y=0)
- Added an intensity slider for moss and sand on walls
- Added support for the fire particle, the ghast and normal torch for Soul Sand Overhaul
- lava noise intensity code improvements and more setting options
- Added a speed line camera effect
- Added letterbox transparency
- Added a noise overlay effect
- Added an option which makes generated normals work with blocklight (and also with handheld light)
  <details><summary>Click to expand for images of generated normals work with blocklight</summary>
  <p>

  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/6ccbb408-7c8f-400f-b934-b21e3fc533e9" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/c2dc6573-b587-409e-b497-ba4c2c2189fe" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/a812db87-3077-4e6c-a805-72412ae5aef2" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/857c6e4b-035e-46f3-9b65-fa5c1cf86279" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/63bc66b4-b58c-4964-b25a-a2147c146ce1" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/1f764f08-dce1-4c51-a3f7-f630e3b35d08" width="500" height="auto" />

  </p>
  </details>
  
- Improved the rain Atmosphere setting (also renamed it). Lightning bolts now are directional!
  <details><summary>Click to expand for images of the directional Lightning bolts (I really love them!)</summary>
  <p>
  
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/03babe53-678f-48e1-ac2a-37219616881a" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/23632d3d-6ebc-4180-a60e-75e79068d07d" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/c8215529-6b0f-46ee-b633-7514055ec2e2" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/6405e138-47c0-4cf3-9c42-d13ab24e4248" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/c52d72ce-51f6-4b93-9404-76bd68be6350" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/ebfce5d5-6147-4d10-b17d-588bd21d2c08" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/a7689b8f-1ede-4159-98b3-bf31a11709b9" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/c68f9663-e143-4cdd-b486-0446626e65ba" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/ba2f4dcd-52a6-4322-902e-8c78f05674d9" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/c2bb3be9-b745-4283-a819-3a786bd20d84" width="500" height="auto" />
  
  </p>
  </details>

- Improved the "No rain above clouds" and the "clearer sky when raining" options
- Removed the night brightness option as it is possible to do the same things with atmospheric multipliers in the base pack
- Added Emissive Flowers
  <details><summary>Click to expand for images of emissive flowers</summary>
  <p>
  
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/70a1967b-a3a6-4f03-b556-97d5150e0d3e" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/662652b4-7c81-4f0c-aa33-4fdb0dc03f20" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/d7d51759-8f24-4b8e-be06-0a2ee4267282" width="500" height="auto" />
  <img src="https://github.com/EuphoriaPatches/ChangelogPrivateDev/assets/46494907/5ee0129d-de14-4581-a525-039aa81c8fca" width="500" height="auto" />
  
  </p>
  </details>

## Fixes
- Fixed Retro outlines with only night vision mode enabled force enabling world outline when not having the night vision effect
- Made lava noise work with labpbr and co, only worked with ipbr before

## Obsolete Options
- Removed blocklight flickering as it is now in the base pack
- Removed Force Glowing Particles Option as it is in the base pack
