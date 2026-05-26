# Awesome Data Format Reverse Engineering [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome reverse engineering resources to make you better! 

Managed by Reversing.ID for the reversing community.

## Introduction

`Data Format Reverse Engineering` focus on representation and interpretation of structured data in stored or transmitted form.

In some cases, format reversing is done in conjunction with software which generate the data.

Most common usage of format reversing is reverse engineering the game assets, which is stored in specializedd containers or undocumented formats for models, textures, animations, audio, etc. 

## Table of Contents

- Resources
    - [Forums & Communities](#forums-communities)
    - [Articles](#articles)
    - [Tutorials](#tutorials)
    - [Practices](#practices)
    - [References](#references)
- Tools
    - [Hex Editors](#hex-editors)
    - [Format Identifier](#format-identifier)
    - [Structure Parser](#structure-parser)
    - [Binary Visualization](#binary-visualization)
    - [String Search](#string-search)
    - [Pattern Search](#pattern-search)
    - [Bundle Extractor](#bundle-extractor)

- - -

## Forums & Communities

Game hacking and reverse engineering

* [ZenHAX](https://zenhax.com/) - game hacking and reversing forum
* [ResHAX](https://reshax.com/) - game reversing archives and formats
* [XeNTaX Forum](https://web.archive.org/web/20231024043128/https://forum.xentax.com/) - game archive and format research forum
* [REGames](https://discord.com/invite/regames-760531247704702996) - discord server for game reversing and file format research
* [The VG Resource](https://discord.com/invite/tsr) - discord server for the VG Resource asset database (models, textures, sprites, sounds, etc)
- [The Cutting Room Floor (TCRF)](https://discord.com/invite/SGeE8dcWR6) - discord server for discovering and documenting unused and debug game content

## Articles

Generic

* [How to crack a Binary File Format](https://www.iwriteiam.nl/Ha_HTCABFF.html) - classic tutorial  on reverse engineering file formats

Game asset 

* [DGTEFF](https://www.gamedevs.org/uploads/the-definitive-guide-to-exploring-file-formats.pdf) - The Definitive Guide to Exploring File Formats
* [Compression Deep Dive]()
* [How to grab models and textures](https://aknavj.github.io/3d/2019/06/10/Grabbing-models-and-textures-from-game-or-3D-application.html) - guide on extracting models and textures from games 

## Tutorials

* [Binary File Format Engineering and Reverse Engineering](https://www.youtube.com/watch?v=8OxtBxXfJHw) - Peter Bindels - ACCU 2023 conference talks on binary file format analysis and reverse engineering techniques
* [Reverse Engineering Game Formats for Fun and Profit](https://www.youtube.com/watch?v=MXbo6y6MCPE) - Spencer Alves - Con West 2020 talk on reverse engineering game file formats

## Practices

Game files reversing practices

* [kovidomi/game-reversing](https://github.com/kovidomi/game-reversing) - beginner learning materials on reverse engineering video games

## References

knowledge bases & format databases for game

* [ArchiveTeam's wiki](http://fileformats.archiveteam.org/wiki/Game_data_files)
- [XeNTaX Wiki](https://web.archive.org/web/20230822181840/https://wiki.xentax.com/index.php/Game_File_Format_Central)

- - - 

## Hex Editors

Hex editor lets you view/edit the binary data of a file.

Multi/cross platform

* [010 Editor](http://www.sweetscape.com/010editor/)
* [Kaitai Struct](https://kaitai.io)
* [wxHexEditor](https://www.wxhexeditor.org/)

Windows 

* [HxD](https://mh-nexus.de/en/hxd/)
* [Hex Workshop](http://www.hexworkshop.com/)
* [Hexinator](https://hexinator.com/)

Mac OS X

* [HexFiend](http://ridiculousfish.com/hexfiend/)

## Format Identifier

* [Binwalk](https://github.com/ReFirmLabs/binwalk)

## Structure Parser

* [010 Editor](http://www.sweetscape.com/010editor/)
* [ImHex](https://github.com/WerWolv/ImHex)
* [Kaitai Struct](https://kaitai.io)

## Binary Visualization

* [Veles](https://codisec.com/veles/)
* [..cantor.dust..](https://sites.google.com/site/xxcantorxdustxx/home)
* [binglide](https://github.com/wapiflapi/binglide)

## String Search

- [bingrep](https://github.com/m4b/bingrep) - grep through binaries

## Pattern Search

- [YARA](https://github.com/virustotal/yara)

## Extractor

Archive extractor

* [QuickBMS](http://aluigi.altervista.org/quickbms.htm) - easily extract and modify file format with support of encryption, compressions, obfuscation, and other algorithms.

Game assets or bundle extractor

* [UABE](https://github.com/DerPopo/UABE) - Unity Assets Bundle Extractor
* [DevXUnityUnpacker](http://devxdevelopment.com/UnityUnpacker)
* [MultiEx Commander](http://multiex.xentax.com/) - multiple game resources archive.
* [isodump](https://github.com/Lameguy64/isodump) - PlayStation ISO content extraction tool.
* [UnkrawerterGBA](https://github.com/MCJack123/UnkrawerterGBA) - GBA ROM extractor and converter for games using the Krawall Sound Engine
* [wad-tools](https://github.com/libertyernie/wad-tools) - WAD archive format (Wii/GameCube) extractor.
* [mymc](https://github.com/uyjulian/mymc) - importing/exporting save games in MAX Drive (.max) and EMS (.psu) formats for PlayStation 2 memory card images.