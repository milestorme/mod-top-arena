﻿# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore
# mod-top-arena
### This is a module for [AzerothCore](http://www.azerothcore.org)
- Latest build status with azerothcore: [![Build Status](https://travis-ci.org/azerothcore/mod-top-arena.svg?branch=master)](https://travis-ci.org/azerothcore/mod-top-arena)

## Description

Creates an NPC with the top arena stats


## How to use ingame

- Spawn with .npc add 55333

## Requirements

My new module requires:

- AzerothCore v1.0.1+


## Installation

```
1) Simply place the module under the `modules` directory of your AzerothCore source. 
2) Import the SQL manually to the right Database (auth, world or characters) or with the `db_assembler.sh`.
3) Re-run cmake and launch a clean build of AzerothCore.
```

## Edit module configuration (optional)

If you need to change the module configuration, go to your server configuration folder (where your `worldserver` or `worldserver.exe` is), copy `modarenatop.conf.dist` to `modarenatop.conf` and edit that new file.


## Credits
* [Poszer](https://github.com/poszer)
* [Talamortis](https://github.com/talamortis)
* [Milestorme](https://github.com/milestorme) 



AzerothCore: [repository](https://github.com/azerothcore) - [website](http://azerothcore.org/) - [discord chat community](https://discord.gg/PaqQRkd)
