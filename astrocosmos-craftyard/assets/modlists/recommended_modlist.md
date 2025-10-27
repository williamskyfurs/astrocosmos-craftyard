# Recommendeds

If your game is running a little slow with VS installed, you have a few options to optimize it, here is a list compiled by <@173254529079312384- 
Note - some of these are fabric exclusive, but DO function with Sinytra Connector just fine. Others are 1.21.x exclusive, or will
not work with Create 5 or Create 6. Always read mod pages for instructions on use, most are very simple.

DH note: DH works best on systems with spare RAM (16GB+), as it exchanges increased RAM usage for optimized CPU/GPU usage rates.
You can use it as intended with 64-128 chunk render, or you can use it with standard MC chunk range for extreme performance boost.

## Server Optimizations
- Better FPS ✅!!!
- Blanket - fabric ~~forge 1.20.1~~
- Lithium ?
- Immediately Fast ✅
- ModernFix ✅-  
  requires "mixin.feature.warn_missing_perf_mods=false" in file config\modernfix-mixins.properties under the commented list
- Redirector[maintained] ✅!!!-  
  will false Fatal with ModernFix, and causes unexpected issues sometimes, but is SO GOOD it is worth trying. 

## Resource Optimizations
- Alternate Current ✅!!!
- Bad Packets ✅!!!
- Chunk Sending ~~forge 1.20.1~~
- Client Crafting ~~forge 1.20.1~~
- Collision Fix ~~forge 1.20.1~~
- FerriteCore ✅
- Fix GPU Memory Leak ✅!!!
- Memory Leak Fix ✅
- Memory Sweep ✅!!!
- Mobtimizations ❌!!!
- Recipe Essentials ?
- Saturn ✅
- MCreatorMemFix ✅!!!

## Load Time Optimizations
- Fast Async World Save ✅!!!
- Fastload ✅!!!
- Noisium ✅
- Server Performance - Smooth Chunk Save ✅!!!
- Smooth Boot ✅

## Assorted Optimizations
- AI Improvements
- Chunky ✅
- EMF
- ETF
- Get It Together, Drops! ✅!!!
- Leaves Be Gone
- Let Me Despawn
- Neruina ✅

## Render Optimizations
- ColorWheel + Patcher  
  (this only works with Create 6 really. Create 5 alternative is Flywheel Oculus Compat)
- Create Better FPS (Ponder ...?)
- Cull (Less) Leaves ✅!!!
- Embeddium ✅
- Embeddium Extra ✅
- Entity Culling ✅
- Flerovium (test for issues with Get It Together, Drops!) ✅!!!
- Oculus ✅
- Out Of Sight
- Async Particles ✅
- Sodium Dynamic Lights ✅!!!
- Sodium Options API ✅!!!
- Sodium Options Mod Compat ✅!!!

## Optimization Tools
- Controlling ✅
- Crash Assistant ✅!!!
- Observable ✅!!!
- Paxi ✅!!!
- Polytone
- Spark ✅

# Incompatibilities
Here are some common incompatibilities as of 18 August 2025:
## Can cause crashes:
- Amendments?
- Connector extras
- Cosmos Heroes
- Does it tick?
- Epic Fight / Weapons of Miracles
- forgero
- FancyMenu / DrippyLoadingScreen
- Groovy mod loader
- liquid burner mod
- Let me despawn 
- Leawinds third person
- Majrusz's Enchantments
- Modern Fix - crash on rendering some clockwork items
- Multiplayer server pause
- ocean realm
- Trajans tanks
- Ready player fun?
- Respawning animals
- regions unexplored
- Rubidium - use embeddium
- Shoulder surfing
- TerraFirmaCraft
- Timeless and classic - use tac-zero
- Webdisplays
## Can cause visual problems (invisible ships etc):
- 2032 world height
- Acedium
- Brute force render culling - auto cannons broken chunks 
- newer than 2.0.0 connectify
- entity culling - tweaking cannons
- immersive portals
- Immersive Optimization - broken contraptions on ships
- Leawinds third person - freeze game on eureka helm
- No see no tick
- Optifine (use embeddium, iris/oculus and simple zoom for alternatives)
- Very many players
## Other problems:
- Axiom - can't interact with ships
- bens sharks - AABB errors
- biome music sounds - no sounds on ships
- plug-in / mod hybrid server
- Serene Seasons Extended - too many physics frames
- Smaller than default world border - can't interact with ships (only 1.16 maybe?)
- simple hats - lag?
- does potato tick - broken physics
- nostalgia tweaks - broken sounds
- Deep Mob Learning: Refrabicated - broken rendering of ships
- Vanilla server jar - unable to move
- Paladin's furniture - ships crashing AND splitting on assembly
- c2me (concurrent chunk management engine) - broken ship assembly (ships disappearing, breaking, etc)