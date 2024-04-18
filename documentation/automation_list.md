
# My automations list for home assistant

<p  align="center">  <a  href="/node-red/"><img  src="https://img.shields.io/badge/Nodered%20FLows-purple"  alt="Red leader standing by, or something"></p> 

- [Home-Wide](/node-red/flows/Home-Wide/flows.json):
  - Announce when occupant arrives home on all speakers in speaker group
  - Get some stats of things happening in the home every 5 minutes
- [Bedroom](/node-red/flows/Bedroom/flows.json):
  - Turn on lights when Cam arrives home after sunset
  - Turn off lights when Cam leaves Home Zone
  - Play music on Surround Sound if Cam arrives home playing spotify or if the toggle is on
  - Turn on sleeper mode when:
     - Sleep confidence is above 70 for 5 mins
     - Time is between 22:30 and 3:00
     - Phone is locked 
     - Phone is charging
     - Sleep mode enabled
  - Turn off sleeper mode when:
     - Time is between 6:30 and 13:00
  - Sleep mode:
     - If sleep lights not on then turn them on
     - Set LED brightness to 1%
     - Set Cam's speaker to 9%
     - Play a random MP3 from a selected mp3 sleep audios folder
     - Turn off sleep lights when sleep mode turned off
  - Sleep mode sets leds to orange at 20% brightness 
  - Turn off lights when plex or xbox is playing media
  -  Turn on lights to a nice purple when plex or xbox is paused
  - Xbox app selector which will turn on xbox and open app selected when i arrive home
  - Morning alarms controlled by dashboard input times and toggle switch
- [Personal](/node-red/flows/Personal/flows.json):
  - Notify Cam's phone when laptop battery less than 30% and not charging
- [Lights](/node-red/flows/Lights/flows.json):
  - Turn on hall, landing and lounge lights at sunset
  - Turn off Lounge smart plug when Lounge TV turns on
- [Group-hangout](/node-red/flows/Group-Hangout/flows.json):
  - Skip selected artists playing from spotify on Family Room or Chromecast speakers
- [Media-Players](/node-red/flows/Media_Players/flows.json):
  - If selected speakers are not playing for 15 mins then set speakers to the right volume
  - Set standard volume on all speakers for the day and certain volume for speakers at night
  - Pause Family Room sonos if media starts playing on Chromecast or NowTV stick#
  - Restart Spotify Connect if it fails to serve
- [System](/node-red/flows/System/flows.json):
  - Send actionable notification when an update is avaliable for HA or any addons