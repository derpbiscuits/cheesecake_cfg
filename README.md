### cheesecake_cfg  1st Jan 2024
cheesecake peek's cfg.. config_cs2 is the main config (cyka2 is now retired) - with all the binds and video settings (I always update this manually) ,
smoke is for smokes, training is for all the training cfgs, crosshair for crosshair toggles, viewmodels for viewmodel toggles -

viewmodels / copypastas / crosshairs all remain the same, other ones are outdated.

### NVIDIA SHADOWPLAY HELP

- changing binds to "none" just press spacebar - so you can get alt+f11 back
  
  
- be sure to change temp files location


- IF THE HOTKEY DOESN'T WORK, TRY ALT + Z FIRST, THEN IF IT DOESNT GO INTO SERVICES.MSC and then restart all things under NVIDIA
  
- if that doesn't work then go to the nvidia geforce folder (program files/nvidia corp) and restart nvidia share

### scenesystem002 error or whatever

- delete old csgo workshop maps
  
- under steamapps\common\Counter-Strike Global Offensive\game\csgo\ 
    
- delete gameinfo.gi (then verify files)

- or game\bin\win64, then delete anything that begins with scenesystem or scenesystem_002 (or for hell the whole folder idk)
- clear your steam download cache, then verify game files

- go to [this thread](https://steamcommunity.com/app/730/discussions/0/3819655068777749970/) and try out everything

- uninstall and reinstall drivers (or just doing a fresh install, seemed to work for me idk why or how)

## temporary fix for not being able to get custom maps
- just host a [server](https://steamcommunity.com/sharedfiles/filedetails/?id=3037135446)
  


## current launch options 
    -allow_third_party_software +fps_max 130 -fullscreen -w 1440 -h 1080 +exec alias +violence_hblood 0 -dev -cl_disablehtmlmotd 1 +volume 0 -nojoy -novid +cl_forcepreload 1 -lv

## FLASHBANG / DEATH SOUND
CSGO SOUND FIX - https://github.com/patrikzudel/PatrikZeros-CSGO-Sound-Fix

##  LIST OF MODS USED (for trainning and other stuff) 

PRACMODE (NADE TRAILS, RETHROW,ETC) https://github.com/splewis/csgo-practice-mode

GLOVES - https://forums.alliedmods.net/showthread.php?t=299977 

WEAPON SKINS - https://forums.alliedmods.net/showthread.php?t=298770

https://github.com/kgns/weapons/releases/tag/v1.7.8 (for anubis collection )

MOVEMENTHUD (the keys on the hud) - https://github.com/Sikarii/movementhud

https://forums.alliedmods.net/showthread.php?p=2658049

GOKZ for everything else kz related... ? - https://github.com/KZGlobalTeam/gokz

https://docs.gokz.org/guides/install-gokz.html

# MISC MODS
retakes - https://forums.alliedmods.net/showthread.php?t=262658

pug setup - https://forums.alliedmods.net/showthread.php?t=244114


### apex folder is for apex stuff

auto exec for boring autoexec shit; superglides for superglides (duh); and the videoconfig goes in C:\Users\USERNAME\Saved Games\Respawn\Apex\local - make sure to lock it so it doesnt change 


### Custom CSS for dotabod

<details>

<summary>changes medal location, W/L text location and size, adds shadow to mmr text</summary> 

## put this in 'custom css' on OBS

```
  /* selects medal-image and positions it */
#__next > div > div.absolute.flex.items-end.justify-end > div:nth-child(2) > div > img {
  position: absolute;
  top: -83px;  
  left: -1051px;
}
/* selects wl-text and positions it */
#__next > div > div.absolute.flex.items-end.justify-end > div:nth-child(1) > div {
  position: absolute;
  top: -115px;
  left: -1051px;
}
/* selects mmr-text and positions it  */
#__next > div > div.absolute.flex.items-end.justify-end > div:nth-child(2) > div > div {
  position: absolute;
  top: -120px;
  left: -1051px;

/* custom "W"-color */
#__next > div > div.absolute.flex.items-end.justify-end > div:nth-child(1) > div > div > span.text-green-400 {
  color: rgb(42, 203, 79);
}
/* custom "L"-color */
#__next > div > div.absolute.flex.items-end.justify-end > div:nth-child(1) > div > div > span.text-red-400 {
  color: rgb(236, 4, 31);
}
/* custom font-size mmr */
#__next > div > div.absolute.flex.items-end.justify-end > div:nth-child(2) > div > div {
  font-size: 18px !important;
}

}
/* custom mmr shadow  */ 
#__next > div > div.absolute.flex.items-end.justify-end > div:nth-child(2) > div > div {
   text-shadow: 1px 1px 2px black;
 
}

/* removes opaque background from elements */
#__next > div > div.absolute.flex.items-end.justify-end .bg-slate-700\/50 {
  background-color: rgba(41, 52, 68, 0); 
}
```

</details>



