# Example ESPHome config files for screens and devices

I use a lot of svg vector graphics. The latest ESPHome does not install svg by default. Use pip to install cairosvg. 

pip install esphome cairosvg

### SDL Display on host

The SDL display platform allows you to use create an ESPHome display on a desktop system running Linux or MacOS. This is particularly useful for designing display layouts, since compiling and running a host binary is much faster than compiling for and flashing a microcontroller target system.

### Guition ESP32-S3-4848S040 480px * 480px Smart Screen

This is a really great little screen. I have a basic getting started config and also a full features one. guition-esp32-s3-4848s040_more_buttons.yaml has a boot screen, a system for dimming the backligh at night and some basic buttons for controlling local and Home Assistant devices.
