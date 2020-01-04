## aFFekopps Home Assistant Configuration 🐵

This is my Home Assistant configuration. My HA Machine is an [Intel NUC BOXNUC6CAYH](https://ark.intel.com/content/www/de/de/ark/products/95062/intel-nuc-kit-nuc6cayh.html) with 4GB RAM and 120GB SSD. It's running [Ubuntu](https://ubuntu.com) 18.04 with [Hass.io](https://www.home-assistant.io/hassio/installation/#alternative-install-on-a-generic-linux-host) in Docker.

![HAVERSION](https://img.shields.io/badge/homeassistant-0.103.5-blue)
![STARS](https://img.shields.io/github/stars/aFFekopp/homeassistant?color=yellow&style=flat-square)
![ISSUES](https://img.shields.io/github/issues-raw/aFFekopp/homeassistant?style=flat-square)
![ACTIVITY](https://img.shields.io/github/commit-activity/w/aFFekopp/homeassistant?style=flat-square)
![LASTCOMMIT](https://img.shields.io/github/last-commit/aFFekopp/homeassistant?style=flat-square)
![SIZE](https://img.shields.io/github/repo-size/aFFekopp/homeassistant?style=flat-square)

## Screenshot

![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/pc/1.jpg)

## Hardware

- [Conbee II](https://phoscon.de/de/conbee2) using ZHA integration
- Philips [Hue Lights](https://www2.meethue.com/de-de/bulbs)
- Philips [Hue Motion Sensors](https://www2.meethue.com/de-de/p/hue-bewegungssensor/8718696743171) in every room
- Philips [Hue Remotes](https://www2.meethue.com/de-de/p/hue-dimmschalter/8718696743157) with custom [3D printed Switch Frames](https://www.thingiverse.com/thing:2905340)
- Xiaomi [Buttons](https://banggood.com/Original-Xiaomi-Mijia-Smart-Home-Zig-bee-Wireless-Smart-Switch-Touch-Button-ON-OFF-WiFi-Remote-Control-Switch-p-1049175.html)
- Xiaomi [Humidity Sensor](https://www.banggood.com/Original-Xiaomi-Mijia-Smart-Home-Temperature-and-Humidity-Sensor-Thermometer-Sensor-p-1046061.html)
- Xiaomi [Door/Window Sensors](https://www.banggood.com/Original-Xiaomi-Intelligent-Door-Window-Sensor-Control-Smart-Home-Suit-Kit-Accessory-p-1017541.html)
- Amazon [Echo Dot](https://www.amazon.de/dp/B07PHPXHQS/) / [Echo Show 8](https://www.amazon.de/dp/B07SNPKX5Y/) / 2x [Echo 3rd Gen.](https://www.amazon.de/dp/B07P64LFFH/)
- [Fire TV 4k](https://www.amazon.de/dp/B079QHMFWC/)

## Hass.io Addons

- [ESPHome](https://esphome.io/)
- [Hass.io Google Drive Backup](https://github.com/sabeechen/hassio-google-drive-backup)
- [MariaDB](https://home-assistant.io/addons/mariadb/)
- [Mosquitto broker](https://home-assistant.io/addons/mosquitto/)
- [Node-RED](https://github.com/hassio-addons/addon-node-red)

## Custom Components

- [Alexa Media Player](https://github.com/custom-components/alexa_media_player)
- [HACS (Home Assistant Community Store)](https://hacs.xyz)
- [Lovelace Gen](https://github.com/thomasloven/hass-lovelace_gen)
- [Node-RED](https://github.com/zachowj/node-red)

## Lovelace Plugins

- [auto-entities](https://github.com/thomasloven/lovelace-auto-entities)
- [Bar Card](https://github.com/custom-cards/bar-card)
- [Button Card](https://github.com/custom-cards/button-card)
- [card-mod](https://github.com/thomasloven/lovelace-card-mod)
- [card-tools](https://github.com/thomasloven/lovelace-card-tools)
- [Custom Header](https://github.com/maykar/custom-header)
- [Lovelace Popup Card](https://github.com/thomasloven/lovelace-popup-card)
- [Mini Graph Card](https://github.com/kalkih/mini-graph-card)
- [Mini Media Player](https://github.com/kalkih/mini-media-player)
- [slider-entity-row](https://github.com/thomasloven/lovelace-slider-entity-row)
- [state-switch](https://github.com/thomasloven/lovelace-state-switch)
- [Vertical Stack In Card](https://github.com/custom-cards/vertical-stack-in-card)
- [Weather Card](https://github.com/bramkragten/weather-card)

## Automations

All of my automations are in Node Red, Home Assistant is just my state machine. Some notable autmations are:

- turning Hue motion sensors off on demand
- actionable notification via telegram when the doorbell is ringing
- turn everything off when everyone is in bed
- presence detection with different states (just arrived, just left, extended away etc.)
- alert when there ist movement in the apartment and nobody is home
- reminder to open the window in the bathroom when a humidity threshold is reached
- music following you around
- guest mode automations
- and many more...

## DIY

- [d1mini](https://www.amazon.de/AZDelivery-D1-Mini-ESP8266-12E-kompatibel/dp/B01N9RXGHY) with [ina219](https://www.amazon.de/INA219-Bi-directional-Current-Arduino-Raspberry/dp/B01MZDKU6D/) current sensor and a [relay](https://www.amazon.de/gp/product/B06XHJ2PBJ/) to grab the doorbell signal and trigger the door opener
- [esp8266](https://www.amazon.de/gp/product/B06Y1LZLLY/) with [hx711](https://www.amazon.de/gp/product/B07MY2PBY4/) and [load cells](https://www.amazon.de/gp/product/B00R1J7VA0/) to check who's in bed

## Aditional Screenshots

#### PC

![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/pc/1-1.jpg) | ![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/pc/2.jpg)
:-------------------------:|:-------------------------:
![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/pc/3.jpg) | ![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/pc/4.jpg)
![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/pc/5.jpg) | ![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/pc/6.jpg)
![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/pc/7.jpg) | ![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/pc/8.jpg)

#### Android

![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/android/1.jpg) | ![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/android/2.jpg) | ![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/android/3.jpg)
:-------------------------:|:-------------------------:|:-------------------------:
![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/android/4.jpg) | ![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/android/5.jpg) | ![](https://raw.githubusercontent.com/aFFekopp/homeassistant/master/docs/screenshots/android/6.jpg)