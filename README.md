# MCRTX Bug Fixes
 The standard open source bug fix resource pack for Minecraft RTX!

## Implemented Fixes:
### Items:
 - Fixed spawn eggs for newer entities using incorrect colours
### Blocks:
 - Enabled PBR on the front face of Chiseled Bookshelf ([MCPE-166159](https://bugs.mojang.com/browse/MCPE-166159))
   - Simply add the necessary texture sets for each Chiseled Bookshelf to take advantage of this.
 - Enabled PBR on the bottom face of Dried Kelp Block 
   - Add PBR textures for the new `dried_kelp_bottom` texture to take advantage of this.
 - Adjusted Water and Glass textures for RTX compatibility
 - Fixed Pale Hanging Moss rendering both sides simultaneously
 - Enabled PBR on lit Redstone Ore and Deepslate Redstone Ore
### Entities:
 - Fixed all entities culling when off screen ([MCPE-110757](https://bugs.mojang.com/browse/MCPE-110757))
 - Fixed Enderman, Phantom, Spider, Cave Spider not applying invisibility
 - Fixed Player and Warden using a black texture when toggling Ray Tracing on
 - Fixed Villager & Zombie Villager clothes failing to render ([MCPE-111414](https://bugs.mojang.com/browse/MCPE-111414))
 - Fixed Tropical Fish fins failing to render
 - Fixed Firework Rockets using a black texture
 - Enabled Warden texture animations with RTX ([MCPE-157438](https://bugs.mojang.com/browse/MCPE-157438))
 - Fixed Iron Golem cracks failing to render
 - Made Minecart TNT and Command Blocks ray traced
 - Made Snow Golem pumpkin head ray traced
 - Fixed Mooshroom mushrooms failing to render
 - Fixed tamed Cats not having a shadow
 - Fixed Breeze texture failing to animate
 - Fixed Wither shield overlay failing to animate, incorrect flash timings ([MCPE-141530](https://bugs.mojang.com/browse/MCPE-141530)) 
