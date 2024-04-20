# Home Assistant Config

![GitHub commit activity](https://img.shields.io/github/commit-activity/t/GingerCam/Home-Assistant-Config)
![GitHub last commit](https://img.shields.io/github/last-commit/GingerCam/Home-Assistant-Config)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues-pr/GingerCam/Home-Assistant-Config)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues-pr-closed/GingerCam/Home-Assistant-Config)

A collection of my updated Home Assistant configuration including:

- [Node Red Automations](/node-red/)
- [Esphome configuration](/esphome/)
- [configuration.yaml](/configuration.yaml)
- [A sorted list of all of my automations](/documentation/automation_list.md)
  
Most of my automations are done in Node Red. These automations will be updated regularly when I create, edit or optimise flows. You may need to edit the flows to suit your setup as you won't have some of the same personal entities as I do.  

## My gear

- Raspberry Pi 4B running Home Assistant OS installed on a micro SD card
- Argon40 Pi 4B case with passive and active cooling controlled by Argon40 addon
- External 500GB hard drive for data, media, backups etc
- ESP8266 NodeMCU based boards

## Esphome

- [ESPMedia](/esphome/espmedia.yaml) - program to control a HA media player entity with ESP based device
- [TempHum](/esphome/temphum.yaml) - program to use a humity/temperature sensor
- [Presence LEDs](/esphome/leds.yaml) - program to track if a device tracker is home by turning on an LED, for example, if turn on LED if person entity is home
- [IR blaster](/esphome/ir.yaml) - program to control Pioneer Surround Sound System and Sony TV

## Additional node red modules

- [node-red-contrib-files-and-folders](https://flows.nodered.org/node/@objectif-lune/node-red-contrib-files-and-folders)
- [node-red-contrib-bigtimer](https://flows.nodered.org/node/node-red-contrib-bigtimer)
- [node-red-contrib-boolean-logic](https://flows.nodered.org/node/node-red-contrib-boolean-logic)
- [node-red-contrib-cast](https://flows.nodered.org/node/node-red-contrib-cast)
- [node-red-contrib-image-tools](https://flows.nodered.org/node/node-red-contrib-image-tools)
- [node-red-contrib-light-transition](https://flows.nodered.org/node/node-red-contrib-light-transition)
- [node-red-contrib-looptimer](https://flows.nodered.org/node/node-red-contrib-looptimer)

I may not have used them all but I'm not too sure which ones i didn't use so it'll just be a list of custom installed nodes
