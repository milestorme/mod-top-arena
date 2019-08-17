# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore
## mod-top-arena 
### This is a module for [AzerothCore](http://www.azerothcore.org)
- Latest build status with azerothcore: [![Build Status](https://travis-ci.org/azerothcore/mod-top-arena.svg?branch=master)](https://travis-ci.org/azerothcore/mod-top-arena)
#### Features:
- An in game NPC that shows Arena 2v2 3v3 4v4 statistics

## Description

- .npc add 55003 Top Arena Rank NPC to see all arena rankings


## How to use ingame

- Talk to NPC

![my new module screenshot](/screenshots/my_module.png?raw=true "my new module screenshot")

<!-- Video example - We can't embed videos on github, only on github.io pages. If you can, make an animated gif of your video instead (but it's not needed) -->
[![Youtube Link](https://i.imgur.com/Jhrdgv6.png)](https://www.youtube.com/watch?v=T6UEX47mPeE)


## Requirements

My new module requires:

- AzerothCore v1.0.1+


## Installation

```
1) Simply place the module under the `modules` directory of your AzerothCore source. 
2) Import the SQL manually to the right Database (auth, world or characters) or with the `db_assembler.sh` (if `include.sh` provided).
3) Re-run cmake and launch a clean build of AzerothCore.
```

## Edit module configuration (optional)

If you need to change the module configuration, go to your server configuration folder (where your `worldserver` or `worldserver.exe` is), copy `my_module.conf.dist` to `my_module.conf` and edit that new file.


## Credits

* [Me](https://github.com/YOUR_GITHUB_NAME) (author of the module): Check out my soundcloud - Join my discord
* [BarbzYHOOL](https://github.com/barbzyhool): best guy <!-- you can remove this small joke or modify it, but if you let the names, we get notified when a new module is made, which is quite cool) -->
* [Talamortis](https://github.com/talamortis): almost best guy <!-- you can remove this small joke or modify it, but if you let the names, we get notified when a new module is made, which is quite cool) -->

AzerothCore: [repository](https://github.com/azerothcore) - [website](http://azerothcore.org/) - [discord chat community](https://discord.gg/PaqQRkd)
