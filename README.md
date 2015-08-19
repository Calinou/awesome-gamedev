

# Awesome Gamedev #

A curated list of good stuff related to the development of games. This list contains *only* [free software] [1] for code, sellers who aren't evil for physical resources, and [free cultural works] [2] for assets.

I have also provided a list of resources which are *not* free, and the reasons why, in the associated Wall of Shame file.

This is released under the GNU Free Documentation License, without invariants or a cover - its text is provided in the LICENSE file.

Table of Contents
=================

- [Assorted Assets](#assorted-assets)
- [Audio](#audio)
  - [Editors](#editors)
  - [Music](#music)
  - [Sound Effects](#sound-effects)
- [Engines](#engines)
  - [General](#general)
  - [HTML5](#html5)
  - [Physics](#physics)
- [Games](#games)
  - [C](#c)
  - [C++](#c)
  - [CoffeeScript](#coffeescript)
  - [Dart](#dart)
  - [ECMAScript](#ecmascript)
  - [Java](#java)
  - [Other/Multiple](#othermultiple)
  - [Python](#python)
  - [Scala](#scala)
- [Graphics](#graphics)
  - [Assorted](#assorted)
  - [Collections](#collections)
  - [Icons](#icons)
  - [Sprites](#sprites)
- [Graphics Tools](#graphics-tools)
  - [Animation](#animation)
  - [Bitmap Compression](#bitmap-compression)
  - [Editors](#editors-1)
  - [Mesh Tools](#mesh-tools)
  - [Spritesheet Tools](#spritesheet-tools)
  - [Texture Tools](#texture-tools)
  - [Voxel Editors](#voxel-editors)
- [Learning Resources](#learning-resources)
  - [Graphics](#graphics-1)
  - [Beginner](#beginner)
  - [Music](#music-1)
  - [Programming](#programming)
  - [Beginner](#beginner-1)
  - [Intermediate](#intermediate)
  - [Reference](#reference)
- [Programming Frameworks and Libraries](#programming-frameworks-and-libraries)
- [Utilities](#utilities)

Assorted Assets
===============

This contains collections of miscellaneous assets of different kinds.

* [Openclipart] [288] - A giant collection of clip art. [CC-0-1.0] [289]
* [OpenGameArt.org] [7] - A large collection of art intended for game development. Various licenses, including free ones.
* [Material Design Icons] [291] - An official icon set from Google following specific guidelines. [CC-BY-4.0] [136] .
* [Wikimedia Commons] [97] - A collection of various assets of all kinds. Various licenses, all CC or free-er.

Audio
=====

## Editors ##

* [Ardour] [130] - The digital audio workstation. [GNU GPLv2] [14] .
* [Audacity] [33] - Software for recording and editing sounds. [GNU GPLv2] [14] .
* [Beast] [133] - Music composition and modular synthesis software. [GNU LGPLv3] [38] .
* [LMMS] [142] - A digital audio workstation. [GNU GPLv2] [14] .
* [MilkyTracker] [34] - Multi-platform application for creating .mod and .xm module files. [GNU GPLv3] [23] 
* [Musagi] [35] - A large and sophisticated music editor. [Expat] [11] .

## Music ##

* [Creative Commons on Bandcamp] [85] - Everything on Bandcamp under a CC-license. Various licenses, all CC.
* [Creative Commons on SoundCloud] [98] - A Creative Commons collection on SoundCloud. Various licenses, all CC.
* [Incompetech] [288] - An artist providing royalty free music of all genres. [CC-BY-3.0] [5] .
* [Jamendo] [287] - A site providing music licensed under the Creatives Commons. Various licenses, all CC.
* [LibreFM] [96] - A big collection of stations, with fully-free music. Licenses allow downloads and reuse.
* [Musopen] [31] - A site dedicated to copyright-free (and culturally free) music. Various licenses, all copyright-free (varies by piece).
* [Open Music Archive] [295] - Digitized out-of-copyright sound recordings. Public domain in the UK.

## Sound Effects ##

* [Bfxr] [290] - A tool to generate sounds. [Apache2.0] [20] .
* [Freesound.org] [30] - A collection of CC-licensed sound effects. Various licenses, all CC.
* [SoundBible's Royalty-free section] [32] - A collection of CC or public-domain-licensed sounds. Various licenses, all CC or public domain.

Engines
=======

These are full-blown game engines.

## General ##

* [AGS] [57] - Implemented in C++. Designed for adventure games. [Artistic License 2.0] [58] .
* [Azul3D] [112] - Implemented in Go. [3-clause BSD] [29] .
* [Backbone] [161] - Implemented in ECMAScript. [Expat] [11] .
* [BananaBread] [162] - Implemented in ECMAScript. A port of Sauerbrauten. [zlib] [45] .
* [Castle Game Engine] [292] - Implemented in ObjectPascal. [GNU LGPLv2] [102] .
* [Chili Source] [262] - Implemented in C++. [Expat] [11] .
* [cocos2d] [75] - Implemented in Python. [3-clause BSD] [29] .
* [cocos2d-android] [263] - Implemented in Java. [3-clause BSD] [29] .
* [Doomsday] [134] - Implemented in C++. [GNU GPLv3] [23] .
* [Duality] [77] - Implemented in C#. [Expat] [11] .
* [Fife] [55] - Implemented in C++. Has Python scripting. Designed for isometric games. [GNU LGPLv3] [38] .
* [Flare] [54] - Implemented in C++. Designed for action RPGs. [GNU GPLv3] [23] .
* [Fluxus] [137] - Implemented in C++. Designed for livecoding worlds. [GNU GPLv2] [14] .
* [gamekit] [293] - Implemented in C++. Scripted using C++, Lua or logic blocks. [Expat] [11] .
* [GamePlay] [266] - Implemented in C++. [Apache2.0] [20] .
* [GDevelop] [60] - Implemented in C++. Targeted at non-programmers. [Expat] [11] (IDE is [GNU GPLv3] [23] ).
* [GNU FreeDink] [47] - Implemented in C++. [GNU GPLv3] [23] .
* [Godot] [51] - Implemented in C++. Has [its own scripting language] [52] . [Expat] [11] .
* [Helm] [83] - Implemented in Haskell. [Expat] [11] .
* [HERITAGE] [123] - Implemented in ECMAScript. Designed for text adventure games. [GNU GPLv3] [23] .
* [Horde3D] [115] - Implemented in C++. [EPLv1] [116] .
* [ioquake3] [202] - Implemented in C. A fork of the Quake III Arena engine. [GNU GPLv2] [14] .
* [Irrlicht] [43] - Implemented in C++. Has a [range of bindings] [44] . [zlib] [45] .
* [JiGS] [268] - Implemented in PHP. Designed for MMORPGs. [GNU GPLv2] [14] .
* [JMonkey] [140] - Implemented in Java. [3-clause BSD] [29] .
* [LambdaHack] [84] - Implemented in Haskell, Designed for roguelikes. [3-clause BSD] [29] .
* [lycheejs] [89] - Implemented in ECMAScript. Designed for construction of HTML5 or native SDL games. [Expat] [11] .
* [Ogre3D] [41] - Implemented in C++. Has a [range of bindings] [42] . [Expat] [11] .
* [Panda3D] [119] - Implemented in C++. Has a Python interface. [3-clause BSD] [29] .
* [Ren'Py] [107] - Implemented in Python. Designed for visual novels. [Expat] [11] , with some parts under [GNU LGPLv3] [38] .
* [qfusion] [206] - Implemented in C++. Designed for FPS games. [GNU GPLv2] [14] .
* [RPGBOSS] [108] - Implemented in Scala. Designed for RPGs made by non-programmers. [GNU AGPLv3] [27] .
* [Sludge] [56] - Implemented in C++. Has its own scripting language. [GNU LGPLv3] [38] .
* [Spearmint] [203] - Implemented in C. Designed for FPS games. [GNU GPLv3] [23] .
* [Spring] [121] - Implemented in C++. Designed for RTS games. [GNU GPLv2] [14] .
* [Turbulenz] [277] - Implemented in ECMAScript. [Expat] [11] .
* [Torque2D] [63] - Implemented in C++. Has its own scripting language. [Expat] [11] .
* [Torque3D] [61] - Implemented in C++. Has [its own scripting language] [62] . [Expat] [11] .
* [Urho3D] [122] - Implemented in C++. Scripted using AngelScript or Lua. [Expat] [11] .
* [voxeliq] [246] - Implemented in C#. Designed for voxel world games. [MsPL] [247] (code).

## HTML5 ##

Unless stated otherwise, these engines are implemented in ECMAScript.

* [Akihabara] [258] - Designed for 8-bit and 16-bit games. [Expat] [11] and [GNU GPLv2] [14] .
* [Babylon.js] [260] - [Apache2.0] [20] .
* [cocos2d-html5] [264] - [Expat] [11] .
* [Coffee2D] [205] - Implemented in CoffeeScript. [Expat] [11] .
* [Crafty.js] [68] - [Expat] [11] and [GNU GPLv3] [23] .
* [Cube] [168] - Designed for voxel games. [WTFPLv2] [169] .
* [kiwi.js] [269] - [Expat] [11] .
* [melonJS] [93] - [Expat] [11] .
* [panda.js] [273] - [Expat] [11] .
* [Phaser] [64] - [Expat] [11] .
* [PlayCanvas] [65] - [Expat] [11] .

## Physics ##

* [ammo.js] [259] - Implemented in ECMAScript. A port of Bullet. [3-clause BSD] [29] .
* [Box2D] [48] - Implemented in C++. Designed to simulate rigid body physics. [zlib] [45] .
* [Bullet] [59] - Implemented in C++. General physics engine. [zlib] [45] .
* [Matter.js] [91] - Implemented in ECMAScript. Physics engine for HTML5. [Expat] [11] .
* [ODE] [117] - Open Dynamics Engine; implemented in C++. Designed to simulate rigid body dynamics. [Original BSD] [118] .
* [Oimo.js] [272] - Implemented in ECMAScript. [Expat] [11] .
* [Physics.js] [274] - Implemented in ECMAScript. [Expat] [11] .

Games
=====

These are meant to serve as examples for your own work, or foundations to built upon.

I have endeavoured to provide both code and asset licenses here - if no asset license is listed, assume it to be non-free or questionably-free. These entries may be removed upon clarification.

## C ##

* [2048-cli] [216] - A CLI version of 2048. [Expat] [11] (code), no significant assets.
* [2048-in-terminal] [217] - A CLI version of 2048. [Expat] [11] (code), no significant assets.
* [Craft] [226] - A 3D voxel world game. [Expat] [11] (code and assets).
* [Curse of War] [234] - A fast-paced strategy game. [GNU GPLv3] [23] (code and assets).
* [edgar] [214] - A 2D platform game with a persistent world. [GNU GPLv2] [14] (code), various free culture licenses (assets).
* [FallingTime] [196] - An arcade game. [GNU GPLv2] [14] (code), various CC (no NC or ND) (assets).
* [Taisei] [199] - [Expat] [11] (code and assets), [GNU GPLv2] [14] for one font.
* [Turtle Arena] [204] - Third-person action game. [GNU GPLv3] [23] (code), various free culture licenses (assets).
* [Wizznic] [219] - A puzzle game. [GNU GPLv3] [23] (code and assets).

## C++ ##

* [Battle for Wesnoth] [244] - A turn-based strategy game. [GNU GPLv2] [14] (code and assets).
* [Blackvoxel] [225] - A voxel exploration and crafting game. [GNU GPLv3] [23] (code and assets).
* [Clonepoint] [193] - [GNU GPLv3] [23] (code), various CC (no NC or ND) (assets).
* [colobot] [233] - A robot-based strategy game. [GNU GPLv3] [23] (code and assets).
* [Egooboo] [210] - A 3D dungeon crawler in the spirit of NetHack. [GNU GPLv3] [23] (code and assets).
* [endless-sky] [227] - 3D space exploration game. [GNU GPLv3] [23] (code), various CC (no NC or ND) (assets).
* [Freeminer] [228] - A 3D voxel world game. [GNU GPLv3] [23] (code), [CC-BY-SA-3.0] [127] (assets).
* [Megaglest] [250] - A 3D RTS game. [GNU GPLv3] [23] (code), [CC-BY-SA-3.0] [127] (assets).
* [Minetest] [229] - A 3D voxel world game. [GNU GPLv2] [14] (code), [CC-BY-SA-3.0] [127] (assets).
* [Monster 1] [212] - A JRPG-style game. [3-clause BSD] [29] (code and assets).
* [Monster 2] [213] - A JRPG-style game. [zlib] [45] (code and assets).
* [OpenDungeons] [236] - A version of Dungeon Keeper. [GNU GPLv3] [23] (code), various free culture licenses (assets).
* [SavageWheels] [198] - A car game. [Expat] [11] (code and assets).
* [Seven Kingdoms: Ancient Adversaries] [241] - A strategy game. [GNU GPLv2] [14] (code and assets).
* [Stunt Rally] [223] - A 3D racing game. [GNU GPLv3] [23] (code), various free culture licenses (assets).
* [Supertux] [215] - A platformer. [GNU GPLv3] [23] (code), various free culture licenses (assets).
* [SuperTuxKart] [224] - A 3D racing game. [GNU GPLv3] [23] (code), various free licenses (assets).
* [The Powder Toy] [231] - A sandbox falling sand physics game. [GNU GPLv3] [23] (code and assets).
* [Warzone 2100] [248] - An RTS sci-fi game. [GNU GPLv2] [14] (code), various free culture licenses (assets).

## CoffeeScript ##

* [coffee-snake] [176] - A version of Snake. [GNU GPLv3] [23] (code), no significant assets.
* [Zop] [186] - A 'connect the dots' game. [Expat] [11] (code), no significant assets.

## Dart ##

* [Hauberk] [190] - A roguelike. [Expat] [11] (code), no significant assets.
* [Pop, Pop, Win!] [183] - A version of Minesweeper. [3-clause BSD] [29] (code and assets).

## ECMAScript ##

* [A Dark Room] [173] - A text adventure game. [MPLv2] [166] (code), no significant assets.
* [Blockrain.js] [177] - A version of Tetris. [Expat] [11] (code and assets).
* [BrowserQuest] [165] - An MMORPG. [MPLv2] [166] (code), [CC-BY-SA-3.0] [127] (assets).
* [Clumsy Bird] [149] - A version of Flappy Bird. [Expat] [11] (code and assets).
* [Drunken Viking] [178] - A top-down puzzle game. [Expat] [11] (code), various CC (no NC or ND) (assets).
* [Freeciv-web] [167] - A port of Freeciv. [GNU GPLv3] [23] and [GNU AGPLv3] [27] (code and assets).
* [Hextris] [179] - A puzzle game inspired by Tetris. [GNU GPLv3] [23] (code), no significant assets.
* [ludum-dare-28] [180] - [CC-BY-4.0] [136] (code and assets).
* [Masonry-JavaScript-Tetris-Clone] [252] - Exactly what it says on the tin. [Expat] [11] (code and assets).
* [Parity] [181] - [Expat] [11] (code), no significant assets.
* [Prism] [184] - A colour-matching game. [Expat] [11] (code), no significant assets.
* [Roguish] [163] - A roguelike. [3-clause BSD] [29] (code and assets).
* [Snake] [157] - A version of Snake. [Expat] [11] (code), no significant assets.
* [Space Crusade][160] - A space game. [Expat][11] (code), [CC0][49] (assets).
* [Space Shooter] [158] - Simple space shooting game. [Expat] [11] (code).
* [Sorades 13k] [159] - A scrolling shooter. [CC-BY-SA-3.0] [127] (code and assets).
* [Squirts] [191] - [Expat] [11] (code and assets).
* [TransCube] [185] - A 2D puzzle platformer. [GNU GPLv3] [23] (code), [CC-BY-SA-4.0] [125] (assets).

## Java ##

* [Ned et les maki] [221] - A 3D puzzle game. [Expat] [11] (code), [FALv1.3] [222] (assets).
* [Newton Adventure] [220] - A puzzle game. [3-clause BSD] [29] (code), various CC (no NC or ND) (assets).
* [PuzzleGame] [257] - A slider puzzle game. Uses Android port of Cocos2D engine. [Expat] [11] (code and assets).
* [Terasology] [230] - A 3D voxel world game. [Apache2.0] [20] (code and assets).

## Other/Multiple ##

* [Cataclysm: Dark Days Ahead] [207] - A roguelike set in a post-apocalyptic world. [CC-BY-3.0] [5] (code), [CC-BY-SA-3.0][127] (assets).
* [DynaDungeons] [194] - A version of Bomberman. Uses Godot engine. [GNU GPLv3] [23] (code), various CC (no NC or ND) (assets).
* [Flare] [211] - A dark fantasy 2D RPG. Uses Flare engine. [GNU GPLv3] [23] (code), [CC-BY-SA-3.0] [127] (assets).
* [Pioneer] [239] - A space exploration game. Implemented in C++ and Lua. [GNU GPLv3] [23] (code), [CC-BY-SA-3.0] [127] (assets).
* [Source of Tales] [242] - An MMORPG. Scripted using Lua (implementation language unclear). [GNU GPLv3] [23] (code), [CC-BY-SA-3.0] [127] and [GNU GPLv3] [23] (assets).
* [Tanks of Freedom][243] - Pixed-based turn-based strategy. Uses Godot engine. [Expat][11] (code and assets).
* [Teeworlds] [200] - Implemented in C and C++. [3-clause BSD] [29] (code), [CC-BY-SA-3.0] [127] (assets).
* [Zero-K] [249] - An RTS game. Uses Spring engine. [GNU GPLv2] [14] (code and assets).

## Python ##

* [Mystic Mine] [197] - [Expat] [11] (code and assets).
* [Unknown Horizons] [245] - A real-time strategy simulation game. [GNU GPLv2] [14] (code), [CC-BY-SA-3.0][127] (assets).

## Scala ##

* [Lichess] [146] - A chess game server. [Expat] [11] (code and assets).

Graphics
========

## Assorted ##

This is a section for everything else that doesn't fit in some other graphics category.

* [Blender 3D Model Repository] [296] - User-submitted 3D models made with Blender. Various licenses, including free ones.
* [CanTree] [10] - Free online tree generator. Generates PNG files. [Expat] [11] .
* [Yobi3D] [13] - A search engine for 3D models that aims to display license information when possible. Various licenses, including free ones.

## Collections ##

This category contains any 'grab-bags' of different kinds of art assets.

* [Free stuff by 7Soul1] [3] - A collection of various game-related assets. Available in PNG. Public domain.
* [openclipart] [6] - A collection of various clip art. Available in PNG. Public domain.
* [Vecteezy] [12] - A collection of vector art. Various Creative Commons licenses.

## Icons ##

* [Game-icons.net] [4] - A constantly-growing collection of black-and-white icons. Available in SVG or PNG. [CC-BY-3.0] [5] .

## Sprites ##

* [SpriteLib] [8] - A big collection of sprites. Available in PNG. [CPL 1.0] [9] .

Graphics Tools
==============

## Animation ##

* [Synfig] [141] - A 2D animation tool. [GNU GPLv2] [14] .

## Bitmap Compression ##

* [pngquant] [16] - A command-line utility for lossy compression of PNG images. Has various front-ends available. [FreeBSD] [17] .
* [Trimage] [18] - A cross-platform tool for losslessly optimizing PNG and JPG files. [Expat] [11] .

## Editors ##

* [AwesomeBump] [41] - A program that generates normal, height, specular or ambient occlusion, roughness or metallic textures. Requires a graphics card with support for OpenGL4 or greater. [GNU LGPLv3] [38] .
* [Blender] [25] - A 3D modelling and rendering editor. [GNU GPLv2] [14] .
* [GIMP] [22] - The GNU Image Manipulation Program. Designed for photo retouching, image composition and similar tasks. [GNU GPLv3] [23] .
* [Hme] [139] - A program for creating, manipulating and viewing height maps. [GNU GPLv2] [14] .
* [Inkscape] [24] - A vector image editing program. [GNU GPLv2] [14] .
* [Krita] [25] - A digital painting and illustration program. [GNU GPLv2] [14] .
* [MakeHuman] [26] - A tool for making 3D characters. [GNU AGPLv3] [27] .
* [MyPaint] [81] - A natural materials painting and drawing emulator. [GNU GPLv2] [14] .
* [NeoTextureEdit] [37] - An easy-to-use, graph-based, procedural texture editor. [GNU LGPLv3] [38] .
* [ngPlant] [105] - A 3D plant modelling software suite. [GNU GPLv2] [14] .
* [NormalMapOnline] [40] - An online normal-mapping tool. [Expat] [11] .
* [Overlap2D] [19] - An engine-agnostic game level and UI editor. [Apache2.0] [20] .
* [Synfig Studio] [104] - 2D animation software. [GNU GPLv2] [14] .
* [Tiled] [21] - Easy-to-use and flexible tile map editor. [GNU GPLv2] [14] and [FreeBSD] [17] .

## Mesh Tools ##

* [MeshLabs] [103] - A portable system for the processing and editing of unstructured 3D triangular meshes. [GNU GPLv2] [14] .

## Spritesheet Tools ##

* [Aseprite] [13] - Animated sprite editor and pixel art tool. [GNU GPLv2] [14] .
* [Piskel] [15] - Online pixel art and animated sprite creator. [GNU AGPLv3] [27] .

## Texture Tools ##

* [TextureGeneratorOnline] [39] - An online tool for texture generation. [Expat] [11] .

## Voxel Editors ##

* [Sproxel] [28] - A 3D interface for quickly editing and creating voxel-based 3D models. [3-clause BSD] [29] .

Learning Resources
==================

These are all collections of information to help you learn about things that might be necessary for developing games.

We aim for *complete* and *current* resources here whenever possible.

## Graphics ##

Beginner
--------

* [Blender 3D: Noob to Pro][286] - A Wikibook for learning how to make 3D graphics with Blender. [CC-BY-SA-3.0][127].


## Music ##

* [LibreMusicProduction] [124] - A community-driven online resource for promoting musical creation and composition using free tools. [CC-BY-SA-4.0] [125] .

## Programming ##

Beginner
--------

* [An Introduction to Python][282] - Pretty much what it says on the tin. [Python License][283].
* [Lua Programming][126] - A completed Wikibook on programming Lua. [CC-BY-SA-3.0][127] .
* [The GNU C Programming Tutorial][280] - An introduction to programming in C by the nice GNU people. PDF. [GNU FDL][281].
* [why's (poignant) Guide to Ruby][237] - An interesting introductory book for Ruby. [CC-BY-SA-3.0][127].

Intermediate
------------

* [Dive Into Python][284] - A Python book for experienced programmers. [GNU FDL][281].
* [Haskell][285] - A very thorough Wikibook on programming Haskell. [CC-BY-SA-3.0][127].
* [Mostly adequate guide to functional programming (in JavaScript)][144] - A book on the fundamentals of functional programming in ECMAScript. [CC-BY-SA-4.0][145].
* [Structure and Interpretation of Computer Programs][240] - A classic programming and teaching text. Designed for teaching Scheme, but can be useful to anyone writing in any language. [CC-BY-SA-4.0][125].

Reference
---------

* [breakouts] [278] - A collection of ECMAScript implementations of Breakout. [Expat][11] .
* [Joey Hess' blog][129] - A collection of posts, many of which are about Haskell use. [CC-BY-4.0][136] 
* [Haskell Programming][128] - A complete wiki of the Haskell programming language. [Expat][11] .

Programming Frameworks and Libraries
===================================

These are programming libraries or low-level code-based tools which are designed to support game programming, but do not provide as much structure or support as an engine would.

* [ActionKid] [82] - A simple video game framework. Implemented in Haskell. [3-clause BSD] [29] .
* [Allegro 5] [36] - A cross-platform library for low-level tasks, like creating windows, accepting user input and so forth. Implemented in C and C++. [3-clause BSD] [29] .
* [Bacon2D] [72] - A framework to ease 2D game development, providing QML elements representing basic game entities. Implemented in C++. [Expat] [11] .
* [bgfx] [261] - A 'build-your-own-engine' rendering library. [FreeBSD] [17] .
* [Chipmunk2D] [74] - A fast and lightweight 2D game physics library. Implemented in C. [Expat] [11] .
* [ChipmunkSharp] [73] - Advanced physics engine library based on Chipmunk. Implemented in C#. [Expat] [11] .
* [Cinder] [113] - A community-developed library for creative coding. Implemented in C++. [FreeBSD] [17] .
* [ClanLib] [131] - A cross-platform toolkit with a primary focus on game creation. Implemented in C++. [ClanLib license] [132] .
* [CutJS] [76] - A lightweight and fast 2D HTML5 rendering engine for cross-platform game development. Implemented in ECMAScript. [Expat] [11] .
* [enchant.js] [65] - A framework for developing simple HTML5 + ECMAScript games. Implemented in ECMAScript. [Expat] [11] .
* [EndGate] [78] - A framework for building HTML5 games. Implemented in TypeScript. [Expat] [11] .
* [GameJs] [279] - A thin library on top of the Canvas API, including some helpful game development modules. [Expat] [11] .
* [Gladiator3D] [267] - A raycasting engine. Implemented in ECMAScript. [Expat] [11] .
* [HaxeFlixel] [79] - A cross-platform development framework, supporting many targets. Implemented in Haxe. [Expat] [11] .
* [Kivy] [80] - Rapid-development library for multi-touch and visual apps on many platforms. Implemented in Python. [Expat] [11] .
* [libGDX] [86] - Cross-platform game development framework. Implemented in Java. [Apache 2.0] [71] .
* [libRocket] [270] - An HTML/CSS-based UI library. Implemented in C++. [Expat] [11] .
* [libSDL2pp] [271] - A set of C++11 bindings for SDL2. Implemented in C++. [3-clause BSD] [29] .
* [LimeJS] [87] - A framework for building fast HTML5 games. Implemented in ECMAScript. [Apache 2.0] [71] .
* [LoomSDK] [88] - A very large and powerful framework for cross-platform 2D game development. Implemented in C++. [Apache 2.0] [71] .
* [LÖVE] [90] - A framework for making 2D games. Implemented in Lua. [zlib] [45] .
* [MINX] [92] - MINX Is Not XNA; a framework resembling XNA. Implemented in C++. [3-clause BSD] [29] .
* [p2.js] [111] - 2D physics library. Implemented in ECMAScript. [Expat] [11] .
* [pixi.js] [275] - A 2D rendering engine. Implemented in ECMAScript. [Expat] [11] .
* [Polycode] [120] - Framework for games and interactive applications. Implemented in C++. Has Lua bindings. [Expat] [11] .
* [PyDark] [95] - Game framework on top of PyGame; designed to be easy to pick up. Implemented in Python. [Expat] [11] .
* [PyGame] [106] - A set of modules designed for writing games. Implemented in Python. [GNU LGPLv2] [102] .
* [Quasi-Engine] [276] - A set of Qt-based tools for game development. Implemented in C++. [GNU GPLv3] [23] .
* [SDL] [46] - Another cross-platform library for low-level tasks, like creating windows, accepting user input, and so forth. Implemented in C. [zlib] [45] .
* [SFML] [109] - Simple and Fast Multimedia Library; a multi-platform, multi-language, multimedia interface to various computer hardware. Implemented in C++. Has a [range of bindings] [110] . [3-clause BSD] [29] .
* [Three.js] [69] - A library that makes WebGL easy to use. Implemented in ECMAScript. [Expat] [11] .
* [voxel.js] [67] - A multi-component framework for bulding voxel games for modern browsers. Implemented in ECMAScript. [3-clause BSD] [29] .

Utilities
=========

This is a catch-all category for things that don't fit anywhere else.

* [Assimp] [100] - Open Asset Import Library; a portable way to import various well-known 3D model formats in a uniform manner. Implemented in C++, with a range of bindings. [3-clause BSD] [29] .
* [Easel.js] [265] - Provides a range of tools to make working with the HTML5 Canvas API easier. Implemented in ECMAScript. [Expat] [11] .
* [gmsh] [138] - A 3D finite-element grid generator with a built-in CAD engine and post-processor. [GNU GPLv2] [14] .
* [libnoise] [101] - A portable coherent noise-generation library. Implemented in C++. [GNU LGPLv2] [102] .
* [Monkey] [94] - A next-generation games programming language. Implemented in C++. [zlib] [45] .
* [PhysicsFS] [99] - A library to provide abstract access to various archives. [zlib] [45] .
* [ScummVM] [53] - A program which allows you to run certain classic graphical point-and-click adventure games, provided you already have their data files. [GNU GPLv2] [14] .
* [WorldForge] [135] - Provides everything needed to create your own free software MMORPG. [GNU GPLv3] [23] (or a compatible license).


[1]: https://www.fsf.org/about/what-is-free-software
[2]: http://freedomdefined.org/Definition
[3]: http://7soul1.deviantart.com/gallery/44815788/Free-Stuff
[4]: http://game-icons.net/
[5]: https://creativecommons.org/licenses/by/3.0/
[6]: https://openclipart.org/
[7]: http://opengameart.org/
[8]: http://www.widgetworx.com/spritelib/
[9]: https://directory.fsf.org/wiki/License:CPLv1.0
[10]: http://arnaud.ile.nc/cantree/generator.php
[11]: https://directory.fsf.org/wiki/License:Expat
[12]: http://www.vecteezy.com/
[13]: http://www.aseprite.org/
[14]: https://www.gnu.org/licenses/old-licenses/gpl-2.0.html
[15]: http://www.piskelapp.com/
[16]: http://pngquant.org/
[17]: https://directory.fsf.org/wiki?title=License:FreeBSD
[18]: https://github.com/Kilian/Trimage
[19]: http://overlap2d.com/
[20]: https://directory.fsf.org/wiki/License:Apache2.0
[21]: http://www.mapeditor.org/
[22]: http://www.gimp.org/
[23]: https://www.gnu.org/licenses/gpl.html
[24]: https://inkscape.org/en/
[25]: https://www.blender.org/
[26]: http://www.makehuman.org/
[27]: https://www.gnu.org/licenses/agpl.html
[28]: http://sproxel.blogspot.com.br/p/about-sproxel.html
[29]: https://directory.fsf.org/wiki/License:BSD_3Clause
[30]: http://www.freesound.org/
[31]: https://musopen.org/
[32]: http://soundbible.com/royalty-free-sounds-1.html
[33]: http://audacity.sourceforge.net/
[34]: http://milkytracker.org/?about
[35]: http://www.drpetter.se/project_musagi.html
[36]: http://alleg.sourceforge.net/readme.html
[37]: http://neotextureedit.sourceforge.net/
[38]: https://www.gnu.org/licenses/lgpl.html
[39]: https://cpetry.github.io/TextureGenerator-Online/
[40]: https://cpetry.github.io/NormalMap-Online/
[41]: http://www.ogre3d.org/
[42]: https://en.wikipedia.org/wiki/OGRE#OGRE_ports_and_wrappers
[43]: http://irrlicht.sourceforge.net/
[44]: https://en.wikipedia.org/wiki/Irrlicht_Engine
[45]: https://directory.fsf.org/wiki/License:Zlib
[46]: https://www.libsdl.org/
[47]: https://www.gnu.org/software/freedink/
[48]: http://box2d.org/about/
[49]: https://creativecommons.org/publicdomain/zero/1.0/

[51]: http://www.godotengine.org/
[52]: https://en.wikipedia.org/wiki/Godot_%28game_engine%29#Scripting
[53]: http://scummvm.org/
[54]: https://github.com/clintbellanger/flare-engine/
[55]: http://fifengine.net/
[56]: https://opensludge.github.io/
[57]: https://github.com/adventuregamestudio/ags
[58]: https://directory.fsf.org/wiki/License:ArtisticLicense2.0
[59]: http://bulletphysics.org/wordpress/
[60]: http://www.compilgames.net/
[61]: https://www.garagegames.com/products/torque-3d
[62]: https://www.garagegames.com/products/torque-3d/overview/programming
[63]: https://www.garagegames.com/products/torque-2d
[64]: http://phaser.io/
[65]: https://playcanvas.com/

[67]: http://voxeljs.com/
[68]: http://craftyjs.com/
[69]: http://threejs.org/

[71]: https://directory.fsf.org/wiki/License:Apache2.0
[72]: http://bacon2d.com/
[73]: https://github.com/netonjm/ChipmunkSharp
[74]: https://chipmunk-physics.net/
[75]: http://python.cocos2d.org/
[76]: http://cutjs.org/
[77]: http://duality.adamslair.net/
[78]: http://endgate.net/
[79]: http://haxeflixel.com/
[80]: http://kivy.org/#home
[81]: http://mypaint.intilinux.com/
[82]: https://github.com/egonSchiele/actionkid
[83]: http://helm-engine.org/
[84]: https://github.com/LambdaHack/LambdaHack
[85]: https://bandcamp.com/tag/creative-commons
[86]: http://libgdx.badlogicgames.com/
[87]: http://www.limejs.com/
[88]: http://loomsdk.com/
[89]: http://lycheejs.org/index.html
[90]: https://love2d.org/
[91]: http://brm.io/matter-js/
[92]: http://libminx.org/
[93]: http://melonjs.org/
[94]: http://www.monkey-x.com/
[95]: http://www.pydark.com/
[96]: https://libre.fm/
[97]: https://commons.wikimedia.org/wiki/Main_Page
[98]: https://soundcloud.com/groups/creative-commons
[99]: https://icculus.org/physfs/
[100]: http://assimp.sourceforge.net/
[101]: http://libnoise.sourceforge.net/
[102]: https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html
[103]: http://meshlab.sourceforge.net/
[104]: http://www.synfig.org/cms/
[105]: http://ngplant.org/
[106]: http://pygame.org/wiki/about
[107]: http://www.renpy.org/
[108]: http://rpgboss.com/
[109]: http://www.sfml-dev.org/index.php
[110]: http://www.sfml-dev.org/download/bindings.php
[111]: https://schteppe.github.io/p2.js/
[112]: http://azul3d.org/
[113]: http://libcinder.org/

[115]: http://www.horde3d.org/
[116]: https://directory.fsf.org/wiki/License:EPLv1.0
[117]: http://www.ode.org/
[118]: https://directory.fsf.org/wiki/License:BSD_4Clause
[119]: https://www.panda3d.org/
[120]: http://polycode.org/
[121]: https://springrts.com/
[122]: https://urho3d.github.io/
[123]: https://notabug.org/SylvieLorxu/HERITAGE
[124]: http://libremusicproduction.com/
[125]: https://creativecommons.org/licenses/by-sa/4.0/
[126]: https://en.wikibooks.org/wiki/Lua_Programming
[127]: https://creativecommons.org/licenses/by-sa/3.0/
[128]: https://wiki.haskell.org/Haskell
[129]: https://joeyh.name/blog/about/
[130]: https://ardour.org/
[131]: http://www.clanlib.org/index.html
[132]: http://www.clanlib.org/license.html
[133]: https://testbit.eu/wiki/Beast_Home
[134]: http://www.dengine.net/engine
[135]: http://www.worldforge.org/
[136]: https://creativecommons.org/licenses/by/4.0/
[137]: http://www.pawfal.org/fluxus/
[138]: http://geuz.org/gmsh/
[139]: http://hme.sourceforge.net/
[140]: http://jmonkeyengine.org/
[141]: www.synfig.org/cms/
[142]: https://lmms.io/

[144]: https://github.com/DrBoolean/mostly-adequate-guide
[145]: https://creativecommons.org/licenses/by-sa/4.0/
[146]: https://github.com/ornicar/lila
[147]: https://github.com/dmcinnes/HTML5-Asteroids
[148]: https://github.com/budnix/ball-and-wall
[149]: https://github.com/ellisonleao/clumsy-bird
[150]: https://github.com/leereilly/Coil
[151]: https://github.com/redbluegames/game-off-2013
[152]: https://github.com/varunpant/CrappyBird
[153]: https://github.com/MattSurabian/DuckHunt-JS
[154]: https://github.com/operasoftware/Emberwind
[155]: https://github.com/razh/game-off-2013
[156]: https://github.com/petarov/game-off-2012
[157]: https://github.com/jrgdiz/snake
[158]: https://github.com/Couchfriends/Space-Shooter
[159]: https://github.com/maettig/starship-sorades-13k
[160]: https://github.com/Loopeex/space-crusade
[161]: https://github.com/martindrapeau/backbone-game-engine
[162]: https://github.com/kripken/BananaBread
[163]: https://github.com/CamHenlin/Roguish
[164]: https://github.com/antionio/game-off-2013
[165]: https://github.com/mozilla/BrowserQuest
[166]: https://directory.fsf.org/wiki/License:MPLv2.0
[167]: https://github.com/freeciv/freeciv-web
[168]: https://github.com/morozd/blk-game
[169]: https://github.com/Nurgak/Cube-engine
[170]: https://github.com/Q42/0hn0
[171]: https://github.com/Q42/0hh1
[172]: https://github.com/gabrielecirulli/2048
[173]: https://github.com/doublespeakgames/adarkroom
[174]: https://github.com/cxong/Beatrix
[175]: https://github.com/sweetcarolinagames/BitBot
[176]: https://github.com/dommmel/coffee-snake
[177]: https://github.com/Aerolab/blockrain.js
[178]: https://github.com/cxong/DrunkenViking
[179]: https://github.com/Hextris/hextris
[180]: https://github.com/antila/ludum-dare-28
[181]: https://github.com/abejfehr/parity
[182]: https://github.com/Zolmeister/pond
[183]: https://github.com/dart-lang/sample-pop_pop_win
[184]: https://github.com/Zolmeister/prism
[185]: https://github.com/jeroenverfallie/ggo13-transcube
[186]: https://github.com/Zolmeister/zop
[187]: https://github.com/particle-clicker/particle-clicker
[188]: https://github.com/lpinca/binb
[189]: https://github.com/cshepp/candyjam/
[190]: https://github.com/munificent/hauberk
[191]: https://github.com/KrofDrakula/squirts
[192]: https://github.com/fernjager/game-off-2013
[193]: https://github.com/rohit-n/Clonepoint
[194]: https://github.com/akien-mga/dynadungeons
[195]: https://github.com/BlkStormy/epic-inventor
[196]: https://github.com/cxong/FallingTime
[197]: https://github.com/koonsolo/MysticMine
[198]: https://github.com/petarov/savagewheels
[199]: https://github.com/laochailan/taisei
[200]: https://github.com/teeworlds/teeworlds/
[201]: https://github.com/albertz/openlierox
[202]: https://github.com/ioquake/ioq3
[203]: https://github.com/zturtleman/spearmint
[204]: https://github.com/Turtle-Arena/turtle-arena-code
[205]: https://github.com/LanJian/coffee2d
[206]: https://github.com/Warsow/qfusion
[207]: https://github.com/CleverRaven/Cataclysm-DDA

[209]: https://github.com/jwvhewitt/dmeternal
[210]: https://github.com/egoboo/egoboo
[211]: https://github.com/clintbellanger/flare-game
[212]: https://github.com/Nooskewl/monster
[213]: https://github.com/Nooskewl/monster-rpg-2
[214]: https://github.com/riksweeney/edgar
[215]: https://github.com/SuperTux/supertux
[216]: https://github.com/Tiehuis/2048-cli
[217]: https://github.com/alewmoose/2048-in-terminal

[219]: https://github.com/DusteDdk/Wizznic
[220]: https://github.com/devnewton/newton_adventure
[221]: https://github.com/devnewton/nedetlesmaki
[222]: https://directory.fsf.org/wiki/License:Free-Art-L-v1.3
[223]: https://github.com/stuntrally/stuntrally
[224]: https://github.com/supertuxkart/stk-code
[225]: https://github.com/Blackvoxel/Blackvoxel
[226]: https://github.com/fogleman/Craft
[227]: https://github.com/endless-sky/endless-sky
[228]: https://github.com/freeminer/freeminer
[229]: https://github.com/minetest/minetest
[230]: https://github.com/MovingBlocks/Terasology
[231]: https://github.com/simtr/The-Powder-Toy

[233]: https://github.com/colobot/colobot
[234]: https://github.com/a-nikolaev/curseofwar
[235]: https://github.com/SimHacker/micropolis
[236]: https://github.com/OpenDungeons/OpenDungeons
[237]: http://mislav.uniqpath.com/poignant-guide/book/chapter-1.html
[238]: https://github.com/henkboom/pax-britannica
[239]: https://github.com/pioneerspacesim/pioneer
[240]: https://mitpress.mit.edu/sicp/full-text/book/book.html
[241]: https://github.com/the3dfxdude/7kaa
[242]: https://github.com/tales/sourceoftales
[243]: https://github.com/w84death/Tanks-of-Freedom
[244]: https://github.com/wesnoth/wesnoth
[245]: https://github.com/unknown-horizons/unknown-horizons
[246]: https://github.com/int6/voxeliq
[247]: https://directory.fsf.org/wiki/License:MsPL
[248]: https://github.com/Warzone2100/warzone2100
[249]: https://github.com/ZeroK-RTS/Zero-K
[250]: https://github.com/MegaGlest/megaglest-source
[251]: https://github.com/gamedolphin/Lost-Beneath-The-Surface
[252]: https://github.com/gamedolphin/Masonry-JavaScript-Tetris-Clone
[253]: https://github.com/gamedolphin/javascript_snake
[254]: https://github.com/gamedolphin/follow_me_javascript_simon_clone
[255]: https://github.com/chuvidi2003/GidiGames
[256]: https://github.com/watabou/pixel-dungeon
[257]: https://github.com/chuvidi2003/PuzzleGame
[258]: https://github.com/Akihabara/akihabara
[259]: https://github.com/kripken/ammo.js
[260]: https://github.com/BabylonJS/Babylon.js
[261]: https://github.com/bkaradzic/bgfx
[262]: https://github.com/ChilliWorks/ChilliSource
[263]: https://github.com/ZhouWeikuan/cocos2d/tree/master/cocos2d-android
[264]: https://github.com/cocos2d/cocos2d-html5
[265]: https://github.com/CreateJS/EaselJS/
[266]: https://github.com/gameplay3d/GamePlay
[267]: https://github.com/krotik/gladiator_3d
[268]: https://github.com/Techbot/JiGS-PHP-RPG-engine
[269]: https://github.com/gamelab/kiwi.js
[270]: https://github.com/librocket/librocket
[271]: https://github.com/AMDmi3/libSDL2pp
[272]: https://github.com/lo-th/Oimo.js
[273]: https://github.com/ekelokorpi/panda.js-engine
[274]: https://github.com/wellcaffeinated/PhysicsJS
[275]: https://github.com/pixijs/pixi.js
[276]: https://github.com/INdT/Quasi-Engine
[277]: https://github.com/turbulenz/turbulenz_engine
[278]: https://github.com/city41/breakouts
[279]: https://github.com/GameJs/gamejs
[280]: http://markburgess.org/CTutorial/GNU-ctut.pdf
[281]: https://www.gnu.org/licenses/fdl.html
[282]: http://www.network-theory.co.uk/docs/pytut/
[283]: https://directory.fsf.org/wiki?title=License:Python2.0.1
[284]: http://www.diveintopython.net/
[285]: https://en.wikibooks.org/wiki/Haskell
[286]: https://en.wikibooks.org/wiki/Blender_3D:_Noob_to_Pro
[287]: https://www.jamendo.com/
[288]: https://openclipart.org/
[289]: https://creativecommons.org/publicdomain/zero/1.0/
[290]: http://www.bfxr.net/
[291]: https://github.com/google/material-design-icons
[292]: http://castle-engine.sourceforge.net/
[293]: https://github.com/gamekit-developers/gamekit
[294]: http://incompetech.com/music/royalty-free/
[295]: http://www.openmusicarchive.org/
[296]: http://www.blender-models.com/
