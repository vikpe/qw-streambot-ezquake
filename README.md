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

### Ammo boxes, health boxes, megahealth
> Located in [/qw/textures/bmodels/](https://github.com/vikpe/qw-streambot-ezquake/tree/main/qw/textures/bmodels)

**Source**: [Colorized QRP models and bmodels](https://gfx.quakeworld.nu/details/372/colorized-qrp-models-and-bmodels/) from the [Quake Revitalization Project (QRP)](http://qrp.quakeone.com/downloads/).

* Animations on health packs and mega removed.

<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/med3_0.png" height="64"> &nbsp; <img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/+0_med25.png" height="64"> &nbsp; <img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/+0_med100.png" height="64"> 

* Cells and rockets with modified HUE / brightness.

<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/shot0sid.png" height="64"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/nail0sid.png" height="64"> &nbsp;
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/batt1sid.png" height="64"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/rock1sid.png" height="64"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/bmodels/rock0sid.png" height="64"> 

### Armors
> Located in [/qw/textures/models/](https://github.com/vikpe/qw-streambot-ezquake/tree/main/qw/textures/models)

**Source**: [Armors - faithfull by PrimeviL](https://gfx.quakeworld.nu/details/44/armors-faithfull-/) 

* Modified HUE / brightness.

[GA](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/armor_0.png), [YA](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/armor_1.png), [RA](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/armor_2.png) 

<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/armor_0.png" height="64"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/armor_1.png" height="64"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/armor_2.png" height="64"> 


### Weapons, backpack, projectiles
> Located in [/qw/textures/models/](https://github.com/vikpe/qw-streambot-ezquake/tree/main/qw/textures/models)

**Source**: Original Quake textures

* Modification (HUE -> Colorize).
  * Yellow: `hue: 60, color: 100, lightness: 20`
  * Cyan: `hue: 180, color: 100, lightness: 20`
  
[RL](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/g_rock2_0.png), [GL](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/g_rock_0.png), [LG](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/g_light_0.png), [SNG](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/g_nail2_0.png), [NG](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/g_nail_0.png), [SSG](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/g_shot_0.png), [backpack](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/backpack_0.png): 


<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/g_rock2_0.png" height="48"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/g_rock_0.png" height="48"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/g_nail2_0.png" height="48"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/g_nail_0.png" height="48"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/g_shot_0.png" height="48"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/backpack_0.png" height="48">

[missile](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/missile_0.png), [grenade](https://github.com/vikpe/qw-streambot-ezquake/blob/main/qw/textures/models/grenade_0.png):

<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/missile_0.png" height="64"> &nbsp; 
<img src="https://raw.githubusercontent.com/vikpe/qw-streambot-ezquake/main/qw/textures/models/grenade_0.png" height="64">


## Credits
Thanks to everyone that have provided feedback on the stream (extra thanks to circle, milton, wimpeeh and andeh) and all authors of content uploaded to [QuakeWorld GFX](https://gfx.quakeworld.nu/).
