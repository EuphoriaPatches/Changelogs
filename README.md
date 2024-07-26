# Latest Public Changes
Euphoria Patches dev versions are available on **[Patreon](https://www.patreon.com/SpacEagle17)** or **[Ko-Fi](https://ko-fi.com/spaceagle17)**
## Euphoria Patches 1.3.3
### Changes
- Added a lot of block.properties entries thanks to the community
- Improved Aurora Influence
- Added pink and purple ore entries in block.properties so modded blocks fit better in those new categories
- Added a warning message for all Apple users when they enable ACL instead of crashing the shader
- Added an Autumn Strength option
- Added an alternative Amethyst Block Style
- Locked the dragon death effect and the end crystal vortex option behind ACL for better compat in the future
- Increased the star brightness slider threshold, it now goes up to 3.0
- Improved the look of grass with a changed lightmap curve
- Made spring flowers have an unlimited range again and not be limited around the player only
- Changed the default behaviour of rainbow end rods, and thus also making it now work with ACL
- Renamed the profiles to avoid confusion
### Fixes
- Fixed the AgX tonemap being too quickly black, creating artefacts. And added an AgX saturation option
- Fixed particles glowing INSANELY bright with a tweaked lightmap curve
- Fixed the end portal colors being slightly off
- Fixed the tag implementation breaking on older iris/oculus versions and making the shader not compile (iris 1.4.2 or so)
- Fixed a compile error which broke the shader if colored light fog was turned off and the end portal rays turned on
- Fixed all false positives with the dragon death effect on iris 1.7.2+ (the effect no longer works on iris 1.7.1 so make sure to update)
- Minor fixes and tweaks
## Euphoria Patches 1.3.2
### Changes
- Added a daylight stars option where stars shine during the day
- Added a sun glare intensity slider
- Added an option which decreases the lighting the deeper you submerge in the ocean
- The night cloud remove option now also works with Reimagined clouds
- The Cloud shadow changes intensity depending on the cloud transparency option now
- Improved the emissive warped and nether wart block animation
- Removed the more end stars option and replaced it with another intensity in the end star amount slider
- Added many blocks to block.properties thanks to the community
- Added a frozen time option which freezes all shader animations. Works best with /tick freeze. Perfect for screenshot comparisons
- Added weather particle color multiplier sliders
- Added an end portal beam setting thanks to [@gri573](https://github.com/gri573)!
- Added an option which awakens the souls of soul sand when standing on it
- Mostly add labpbr support back, lava and seasons and overlay noise should now work much better, at least on iris/oculus
- Interactive foliage now works in third person on iris
- Prevent mods which abuse the lightmap to blind you when holding a light source with a light level bigger than 15 (this is cursed from the mod)
- Improved lightmap normals from placed light sources and handheld light sources drastically, they are now as good as they can be
- Added a pinker cherry leaves option
- Added a beacon emission option
- Improved bedrock noise handling in the nether
- Added lightmap curve options
- Added handheld and blocklight lightmap normals intensity sliders
### Fixes
- Fixed Overworld beams breaking light shafts during the day and improved their coexistence with other volumetric effects. They should be fixed for good now
- Fixed Nether Stems and Dragon egg not emitting light with ACL
- Watermark no longer waves underwater
- Fixed the dragon death effect not working in 1.21
- Many effects from EP now work correctly with blindness or darkness
- Prevent sand and moss noise from ever happening in other dimensions except the overworld
## Euphoria Patches 1.3.1
Small Fixes
### Changes
- Fixed Ocean Physics From Physics mod not working
- Fixed 2 compile errors with distant horizons
- Added more modded blocks
## Euphoria Patches 1.3
This version is the biggest update so far, adding so many things it's impossible to sum it up in a message

### Changes
- Updated to Complementary r5.2.1
- Removed the lava column noise option as it is enabled by default and it just looks too good so there is no need to disable it :p
- Tweaked Purple fire gradient
- Added Renko's Cut of Euphoria Patches by [@gri573](https://github.com/gri573)
- Seasons now start in spring and they are by default now 28 Minecraft days long to match the behaviour of the [fabric seasons mod](https://modrinth.com/mod/fabric-seasons)
- Added a starting season option where you can change from which season the cycle starts
- Added Support for many Euphoria Patches features with [Distant Horizons](https://modrinth.com/mod/distanthorizons)
- Added a glitter rain option
- All light level 15 modded light sources (and other light levels with iris 1.7) will automatically work with SSBL now
- All modded cross-model foliage blocks work with SSS and with the new Advanced Colored Lighting system
- Lava lakes in caves under y -55 in the overworld will now also look like the nether lava lakes with the adaptive lava noise preset
- Added separate Border Fog settings (Distance and Density) for all dimensions
- Added glowing raw blocks option
- Added a new end portal effect
- Added a long exposure mode
- Added a tilt-shift option (this is awesome!)
- Interactive foliage has a smoother fallof
- Added A lava edge effect
- The Cloud Height Option now works with Unbound Clouds
- Added Handheld Blocklight Flickering
- Started Adding modded blocks to block.properties
- Added a lava edge setting (only works if ACL is enabled)
- Added Watermark Conditions
- Added an option to view the focus plane of DOF for better control for screenshots. If enabled it is only visible when the GUI is visible, when toggling F1 to take a screenshot it fades away
- [@gri573](https://github.com/gri573) Added an awesome End Crystal Vortex Option (does not work on Mac (requires voxelation) - enables entity shadows)
- The above option also has a healing beam option, only works on an unreleased iris version for now
- Added an ender dragon death animation (does not work on Mac (requires voxelation) - enables entity shadows)
- An atmospheric and lighting multiplier comparison option has been added so people can more easily compare the changes
- Improved the look of Soul Sand Valley Overhaul lava and Purple End Fire Lava, they now look like intended on all lava noise modes.
- Added a cloud render distance slider to control how far or near clouds will appear
- Added an unbound night cloud remover option, because of frequent suggestions :p
- Improved the Epic Thunderstorm option. The contrast is not as drastic anymore. Generated normals now also work with the lightning bolt!
- Added an emissive diamond enchanting table option
- Improved the visuals of crimson nylium and crimson roots with soul sand valley overhaul on.
- Added more information buttons
- Improved details with Soul Sand Valley Overhaul turned on, such as blocklight turning blue even without ACL or SSBL
- Added an SSS toggle
- Removed nether fungi from interactable foliage (for consistency and better looks if 3d RP is used)
- Better Nether and Better End Support was Added by @Acer (Alex)
- Added a new stylistic water style with major help from Helgust for providing the original code
- Improved the look of winter, now foliage is much more dull and dead. A slider was added if one wants to bring back life into them :p
- Sand and moss noise now only work in a distance (configurable) around the player to improve situations where sand gets everywhere. I don't like sand. It's coarse and rough and irritating and it gets everywhere.
- Stars can be turned off by tweaking the star brightness slider (previous star brightness configs don't break yaaaay)
- Added Emin's cave smoke option for ACL
- Added waving sugar cane option, works better with ACL similar to Waving Nether Vines Emin added
- Added a Noise Coated Textures resolution slider
- Added an option to disable Complementary's Water Tweaks
- Added a modified variant of ACES tonemap which does not turn reds into oranges when very bright, only disadvantage is the loss of detail with the emissive redstone block
- Added modded End fog support. The ender beam and ambient light colors change based on the fog color of a modded end biome, vanilla biomes use the Complementary Colors
- End sky colors also change color in modded biomes now, amount can be changed with a slider
- Added a list of what features are iris exclusive to the information file
- Added Polish translation thanks to @Acer (Alex)
- Added higher values for lava emission, at your own risk
- Added a higher quality clouds option
- And MANY minor changes and probably a lot I forgot

### Fixes
- SSS artefacts (a lot of parallel lines) are fixed on snow and ice with the Snow Ice SSS option enabled
- Fixed Purple fire appearing in the nether with labpbr mode on
- Removed some log errors
- Ghast no longer glows blue when damaged when in the Soul Sand Valley and the overhaul option is enabled
- Fix with seasons and overlay noise conflicting with each other
- Fixed End Smoke Setting breaking the border fog
- Fixed Cave Fog Density not working correctly
- Fixed compile error with vanilla clouds, no border fog and aurora influence settings combination. This bug has been roaming around for months
- Fixed MANY Compile Errors
