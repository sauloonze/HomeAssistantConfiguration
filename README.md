# Smart Tiny Home


![](https://github.com/sauloonze/HomeAssistantConfiguration/blob/master/images/home.png)

## Home Assistant Configuration

That is it! My home assistant configuration is here to the community. The project is a WIP as my tiny house is under construction. The dead line is Jul/2019.
I am using two raspberry pi 3b+. The first one a.k.a.(home) runs the heavy load and a second a.k.a.(screen) run a 7inch screen with the dashboard.

## Hardware/Services

- Raspbery Pi 3b+ (home)
  - homeassistant
  - mysql
  - mosquitto
  - zigbee2mqtt
  - nodered
  - monitor

- Raspbery Pi 3b+ (screen)
  - chromioun in kiosk mode
  - pihole

- ESP32
  - MClighthing
  
- Xiaomi
  - 2x Dafang Camera
  - 2x Temperature and Humidity sensors
  - 2x (PIR) Motion sensors
  - 2x Door/Window sensors
  - 2x Buttons
  - 2x Gateway
  
### Packages Used

- Alarm System:
  - [alarm](https://home-assistant.io/components/device_tracker.gpslogger/)
- Camera:
  - [Xiaomi Cameras](https://home-assistant.io/components/device_tracker.gpslogger/)
- Date Time:
  - [sun]
  - [workday]
  - [time_date]
  - [worldclock]
  - [moon]
  - [season]
- Lighting:
  - [mqtt](https://home-assistant.io/components/light.hue/) Desktop 5m LED Strip - DIY ESP
  - [broadlink]
  - [xiaomi-gateway]
- Media:
  - [media_extractor]
  - [tts:google]
  - [media_player]
  - [samsungtv]
  - 2x [Google Home Mini]
- Notifications:
  - [pushbullet](https://home-assistant.io/components/notify.html5/) Push Notifications
- [PiHole](https://home-assistant.io/components/sensor.pi_hole/)
- Presence/Device Tracking:
  - [device_tracker]
  - [monitor](https://home-assistant.io/components/device_tracker.gpslogger/) Uses PI bluetooth to detect device.
  - [ping](https://home-assistant.io/components/device_tracker.gpslogger/)
- Radio: Piece of code found on the internet.
- System Status:
  - [uptime]
  - [systemmonitor]
  - [version]
  - [filesize]
  - [system_health]
- Trash Recycle: Piece of code found on the internet.
- TV Power:
  - [broadlink] Power On and Off using broadlink IR
- Weather:
  - [darksky](https://home-assistant.io/components/sensor.wunderground/)
  - [airvisual]
  - [mold_indicator]
  - [bom]
- [Xiaomi](https://home-assistant.io/components/emulated_hue/)
  - 2x Temp/Humid Sensor
  - 1x Motion Sensor
  - 1x Button
  - 2x Old Gateway
- [Zigbee2mqtt](https://home-assistant.io/docs/z-wave/):
  - 1x Motion Sensor
  - 1x Button

### Components Used

- Lovelace UI
  - tracker-card.js
  - mini-media-player-bundle.js
  - compact-custom-header.js
  - mini-graph-card-bundle.js
  - card-tools.js
  - card-modder.js

- Nodered
  - homeassistant-websocket
  - mqtt

### Automations

- Living room lights controlled based on monitor and time of the day
- Disk, Memory and Temp. alert
- WIP

### Screenshots

- Home
  
![](https://github.com/sauloonze/HomeAssistantConfiguration/blob/master/images/home.png)

- Media
  
![](https://github.com/sauloonze/HomeAssistantConfiguration/blob/master/images/media.png)

- Climate
  
![](https://github.com/sauloonze/HomeAssistantConfiguration/blob/master/images/climate.png)

# TODO

- Export lovelace
- Export node-red flows
- Describe automations
- More screenshots