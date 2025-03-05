# esphome-device-configs

This repo contains the YAML config's for ESPHome devices it created.

## Greenhouse sensor

A sensor in the greenhouse measuring temperature, humidity, air pressure, air quality and rain.
It uses the sensors BME280, PMS5003 and rain sensor.
A SSD1306 oled display show sensor values.
A button is added to be able to scroll through display pages.

## Fan controller

For better air flow in my serverrack when the door is closed, this controller controls 2 Noctua NF-S12A PWM fans and has a DHT11 sensor to measure temperature (and humidity).
A SSD1306 oled display shows the fan speeds and temperature and humidity.

TODO:
- let controller control fan speeds itself based on measured temperature instead of relaying on Home Assistant to do this.
