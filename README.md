![](http://i.imgur.com/TnoYjzI.jpg)

# Installation

Installation is simple. Copy the folder “kerbodynePlus” to your GameData folder.

Make sure you have KSP 1.1 pre-release or higher.


# About

## Summary

Kerbodyne Plus is an end-game parts pack for the game Kerbal Space Program.
[link](https://kerbalspaceprogram.com/)

## Pics

![](http://i.imgur.com/UZEntDe.jpg)

![](http://i.imgur.com/zXRe9xY.jpg)

![](http://i.imgur.com/ZalILxk.jpg)

![](http://i.imgur.com/kLrY8C7.jpg)

![](http://i.imgur.com/DPt3K9c.jpg)

![](http://i.imgur.com/c2kTfjv.jpg)


## Project Goals
* Provide optimized parts for large construction
* Improve end-game play
* Provide beautifully designed parts
* Keep designs grounded in reality (or at worst near-future)
* Remain mod agnostic (Kerbodyne Plus does not support or hinder other mods)

# Release Notes for Stable Release V1.051 - 4/10/2016
* This release will BREAK any saves from Kerbodyne Plus V1.0, so backing up save files is highly encouraged!
* This is an early version of Kerbodyne Plus. Names in cfg files are subject to change, so updating in the future WILL BREAK GAMES.
* A quick update to address a bug with Kerbodyne S6-94640 Tank flag, where the flag texture was unusually distorted.
* Fixed cost issue with the Kerbodyne S6-94640 Tank, Kerbodyne S6-7890 Tank Cluster, and Kerbodyne S6-7890 X4 Tank Cluster, where cost of the part was less than total cost of fuel.
* fixed a few spelling mistakes in part descriptions.
* Many parts are still to come, such as ion engines and the revamped NRAX converter, as well as some other really neat parts! Check out the dev thread for more info: [Link] (http://forum.kerbalspaceprogram.com/index.php?/topic/112686-kerbodyne-plus-development-thread/&page=1)

# Release Notes for Stable Release V1.05 - 4/6/2016
* This release will BREAK any saves from Kerbodyne Plus V1.0, so backing up save files is highly encouraged!
* This is an early version of Kerbodyne Plus. Names in cfg files are subject to change, so updating in the future WILL BREAK GAMES.
* This release of Kerbodyne Plus was mostly made to address issues do to KSP 1.1 pre-release.
* Added new part descriptions for all of the T404 parts.
* Added new resources to all T404 parts.
* Balanced T404 mass and cost variables.
* Fixed a scaling bug with the XL-6 Landing Strut.
* Added new part, T404 Structural Hub
* Changed releaseNotes.tx to releaseNotes.md
* Added new part Kerbodyne PFR-6 Stack Decoupler.
* Replaced the Behemoth booster with the Behemoth Launch System (size 6 9x engine cluster with custom particle and sound effects).
* Added new part S6 B-1x9 "Behemoth" Liquid Fuel Engine.
* Added new part Kerbodyne ADTP-3-6 (adapter fuel tank).
* Fixed a bug where the Kerbodyne PFR-6 Stack Decoupler would sometimes crash the game.
* Added several new parts. See future K+ 1.1 release notes for details.
* Yes, I deleted the T202 to T404 adapter. If I add it back it will look like the T404 to 3.75M adapter (I think the T404 to 3.75M looks good with T202).
* Added bulkhead sort, all the parts have a custom bulkhead of "kp", so you can quickly get to all the Kerbodyne Plus parts. You can also search for "kp" or "kerbodynePlus" in the tag search (as well as "behemoth" or "behe" for all the behemoth parts and "t404" for all the t404 parts). T404, T202, and behemoth have custom bulkhead profiles, so you can sort that way to ("t404", "t202", "behemoth"). 
* I added new tag entries for all parts.
* Rebalanced all the part costs and tech tree placement.
* Increased the size of XL Landing Strut.
* Rebalanced weight and heat tolerance for all parts.
* Added new RSP-A3 Radial Stack Point (acts like a hardpoint with 2 attach nodes. It's physicless so it transfers mass to the part its surface attached to like the cubic octagonal strut).
* Changed the texture for T404 inner walls from orange to black, because in some cases, the t404 b struts were turning orange when zoomed out do to mipmapping.  I'll probably remap the texture to prevent this in the future. 
* Changed the size and placement of the particle effects for Behemoth engines.
* Added the new T404 B-2 and B-3 trusses.
* Added new T202 B-2 integrated truss.
* Added T202 BA-64 Battery Array - 6000 ec
* Added 3 new structural Tank Couplers each with 10 attachment points but different configurations. These new orange structural parts will make up a third tier of construction for the purpose of making even bigger superstructures.
* Added S6 radial decoupler part of the behemoth launch system.
* Added T404 H-3 which replaces the older T404 B-3 (naming was weird before, the size was 2 and it's configuration and purpose are fundamentally different).
* Added Kerbodyne S6-7890 X4 Tank Cluster (4x 7.5m tanks, t404 center) and Kerbodyne S6-7890 Tank Cluster (5x 7.5m tanks, no t404 center).
* Added R-D HLRX4 (behemoth class rcs)
* Changed the Kerbodyne S3 Smart Cone SAS torque from 75 to 300 for 1.1 stability
* Rebuilt the cfg file for XL-6 Landing Strut using 1.1 wheel modules (thanks to @NecroBones @sarbian for their help with this).
* Remodeled all T404 parts adding struts to sidewalls (now they really look like trusses!).
* Remodeled Leviathan Solar Wing increasing total length by 20M. Remade panel animations. Replaced the central mast truss from alpha texture to real geometry. (Each panel has its own collider, making for a part with hundreds of colliders. This causes lag. However, when the part is destroyed every panel tears off quite spectacularly. In ksp 1.1, on my machine, the lag was tolerable. I plan to rebuild this part in the future to accommodate a more compact animation, so will try to optimize the physics at that time).
* Redesigned T404 3.75M Adapter (adapter is now hollow, has cool struts similar the XL-6 Landing leg and now longer holds any electric charge).
* Adjusted the scale of the CM 1 internal space for compatibility with the new 1.1 crew overlays.
* Added new S6 7.5M Fairing (increases to 15 meters in diameter)
* There's an easter egg I left (mistake) I wonder if anyone found it.


# Release Notes for Stable Release V1.0

## Parts Included:

* CM1 24 Kerbal Command Pod
* S3 KL-11 "Behemoth" Liquid Booster (max thrust 8000, ISP 320/295 in vac)
* Kerbodyne K-12 Tank (13163 LF, 16088 Ox, 3.75m profile, 15m tall)
* T404 3.75M Adapter
* T404 A-1, A-2, A-3 Integrated trusses
* T404 B-1, B-2, B-3 Integrated trusses
* T404 Side Panel
* "London" Docking Port (1.25, 2.5, 3.75 variants)
* "Leviathan" Solar Wing (simply massive solar panels)
* XL-6 Landing Strut (3.75M high)

## What's New:

* If you played with the alpha release then many of these parts will look familiar. Everything aside from the docking ports has been remodeled and everything has been retextured.
* All textures are now dds!
* Many naming conventions have been reworked in order to give a more logical relationship to the parts (T404 A-1 and T404 B-2 for example)
* Models were compiled in many instances with more than two materials, and split into separate mesh items, to further optimize memory footprint.

## Todo:

* Part rebalancing (many parts need better mass, heat, and monetary costs.
* More parts!
* Agency missions for those parts! (subject to change)
* Refine part naming conventions
* Further part memory optimizations!


# Credits

## Current Team

* Bonus Eventus — 3d Modeling, CFG design, Project Lead

## Special Thanks

* This mod would not exist without the work of my predecessors nil2work, Bac9, and Roverdude as well as everyone at the addon dev KSP forum.

* I’d also like to thank all the users of Kerbodyne Plus. This is my first mod, so I’ve had to learn quite a lot as the project progressed. Thanks for being patient!


# License

This work and all its files is shared under CC BY-NC-SA 3.0 license. [link](https://creativecommons.org/licenses/by-nc-sa/3.0/)
