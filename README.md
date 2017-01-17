# Competitve Programming
## SublimeText (C++)
Create ``input.io`` file as INPUT in same directory with source code. OUTPUT will be printed in shell.
```
{
	"cmd": ["g++ ${file} && xterm -hold -e \"./a.out < input.io\""], 
	"file_regex": "^(..[^:]*):([0-9]+):?([0-9]+)?:? (.*)$",
	"working_dir": "${file_path}",
	"selector": "source.c++",
	"shell": true
}
```

# Competitive Gaming
## StarCraft 2 
1. Set all graphics quality to LOW then exit StarCraft
2. Edit ``Documents/StarCraft II/variables.txt`` :

```
antialias=0
bakeTerrainLighting=0
creeptrans=1
globalhdr=1
glossmaps=1
GraphicsOptionEffectsDetail=1
GraphicsOptionModelQuality=1
GraphicsOptionOverallQualityVer7[15]=5
GraphicsOptionPortraits=1
GraphicsOptionShaderDetail=1
GraphicsOptionShadowQuality=0
lighting=0
lightingLevel=2
lightingregionmapterrain=1
localhdr=1
lowqualitymodels=0
normalmap=1
particlelod=1
pixellight=1
portraits3d=0
preBlendedCreep=0
sampleFOW=1
shadows=1
shadowmapsize=1
simplifiedCloaking=0
simplifiedShaders=0
spec=1
splatlod=1
textureBasedFOW=1
use20shaders=0
useLowqualitymodels=0
```


## Dota 2 (Quickplay)
Use Dota 2 console
```
dota_ability_quick_cast 1
bind "q" "dota_ability_quickcast 0"
bind "w" "dota_ability_quickcast 1"
bind "e" "dota_ability_quickcast 2"
bind "r" "dota_ability_quickcast 5"
bind "d" "dota_ability_quickcast 3"
bind "f" "dota_ability_quickcast 4"
dota_force_right_click_attack 1
bind A "+chatwheel; chat0" 
alias chat0 "chat_wheel_phrase_0 64;
chat_wheel_phrase_1 69;
chat_wheel_phrase_2 15;
chat_wheel_phrase_3 66;
chat_wheel_phrase_4 76;
chat_wheel_phrase_5 60;
chat_wheel_phrase_6 69;
chat_wheel_phrase_7 70;"
dota_always_show_player_names 0
dota_camera_accelerate 50
dota_camera_disable_zoom 0
dota_camera_speed 3000
dota_disable_range_finder 0
dota_hud_healthbar_number 1
dota_player_units_auto_attack 1
dota_screen_shake 0
fps_max 80
mat_triplebuffered 0
mat_vsync 0
rate 80000
volume 1
```
