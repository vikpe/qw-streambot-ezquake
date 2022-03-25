# Streambot ezQuake setup
> https://www.twitch.tv/vikpe

The setup is optmized for **ezQuake 3.6-dev** on a 27" monitor at 2560x1440 resolution.

## How to download
There are several ways to download these files.

* **A)** [**Download as a single .zip file** (75 mb)](https://github.com/vikpe/qw-streambot-ezquake/archive/refs/heads/main.zip)
* **B)** Clone the repo: `git clone https://github.com/vikpe/qw-streambot-ezquake.git`
* **C)** Browse and download individual files, e.g. specific [textures](#textures) or [the config](https://github.com/vikpe/qw-streambot-ezquake/blob/main/ezquake/configs/streambot.cfg).


## Screenshots
![screenshot 1](.github/screenshot_01.jpg)
![screenshot 2](.github/screenshot_02.jpg)
![screenshot 3](.github/screenshot_03.jpg)
![screenshot 4](.github/screenshot_04.jpg)


## Textures

### Health packs, mega health, ammo boxes
> Located in: [`/qw/textures/bmodels/`](https://github.com/vikpe/qw-streambot-ezquake/tree/main/qw/textures/bmodels)

<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/med3_0.png" height="64"> &nbsp; <img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/+0_med25.png" height="64"> &nbsp; <img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/+0_med100.png" height="64"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/shot0sid.png" height="64"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/nail0sid.png" height="64"> &nbsp;
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/batt1sid.png" height="64"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/rock1sid.png" height="64"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/rock0sid.png" height="64"> 

* **Source**: [Colorized QRP models and bmodels](https://gfx.quakeworld.nu/details/372/colorized-qrp-models-and-bmodels/).
* **Changes**:
  * Removed animation on health packs and mega health.
  * Modified HUE / brightness on cells and rockets.


### Armors
> Located in: [`/qw/textures/models/`](https://github.com/vikpe/qw-streambot-ezquake/tree/main/qw/textures/models)

<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/armor_0.png" height="64"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/armor_1.png" height="64"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/armor_2.png" height="64">

* **Files**: [GA](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/armor_0.png), [YA](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/armor_1.png), [RA](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/armor_2.png)
* **Source**: [Colorized QRP models and bmodels](https://gfx.quakeworld.nu/details/372/colorized-qrp-models-and-bmodels/)
* **Changes**: Modified HUE / brightness for more saturated color.


### Weapons
> Located in: [`/qw/textures/models/`](https://github.com/vikpe/qw-streambot-ezquake/tree/main/qw/textures/models)

![weapons](.github/weapons.jpg)

* **Files**: [SSG](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/g_shot_0.png), [NG](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/g_nail_0.png), [SNG](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/g_nail2_0.png), [GL](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/g_rock_0.png), [RL](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/g_rock2_0.png), [LG](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/g_light_0.png)
* **Source**: Original Quake textures.
* **Changes**: HUE -> Colorize (`hue: 60, color: 100, lightness: 20`)


### Projectiles
> Located in: [`/qw/textures/models/`](https://github.com/vikpe/qw-streambot-ezquake/tree/main/qw/textures/models)

<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/missile_0.png" height="64"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/grenade_0.png" height="64">

* **Files**: [missile](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/missile_0.png), [grenade](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/grenade_0.png)
* **Source**: Original Quake textures.
* **Changes**: HUE -> Colorize (`hue: 180, color: 100, lightness: 20`)


### Map textures
> Located in: [`/qw/textures/`](https://github.com/vikpe/qw-streambot-ezquake/tree/main/qw/textures/)

* **Source**: [Quake Revitalization Project (QRP)](http://qrp.quakeone.com/downloads/)
* **Changes**: JPEG conversion by [Milton](https://www.twitch.tv/Miltonizer) for faster loading time.


## Credits
Thanks to everyone that have provided feedback on the stream (extra thanks to circle, milton, wimpeeh and andeh) and all authors of content uploaded to [QuakeWorld GFX](https://gfx.quakeworld.nu/).
