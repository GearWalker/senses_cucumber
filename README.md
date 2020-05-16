# Using SensesIoT platform with Gravitech Cucumber (Demo)

## Introduction

This is the demonstration for Cucumber, an ESP32-S2 board from Gravitech. Sending temperature from internal (On-Chip) sensor to SensesIoT platform.

## Documentation

This demo uses kconfiglib which is a Python-based extension to the Kconfig system which provides a compile-time project configuration mechanism. Developers can open a terminal-based project configuration menu with the `idf.py menuconfig` build target.

### Kconfig options

- `WiFi SSID` SSID (network name) for the example to connect to.

- `WiFi Password` WiFi password (WPA or WPA2) for the example to use.

- `Maximum retry` Set the Maximum retry to avoid station reconnecting to the AP unlimited when the AP is really inexistent.

- `Senses User ID` An ID number of your Senses services.

- `Senses Device Key` A target key of your Senses device.

- `Senses Widget slot` A widget slot number.

- `Update delay` A time delay in between package.

## Links

- [SensesIoT](https://www.sensesiot.com/)

- [Gravitech Cucumber](https://www.gravitechthai.com/product-detail.php?WP=rUEjoz1yq3EZoz1iM2A0G2zDrYyj4T1zqlMZG22DM7y04TyjrPMjZT1Cq5OZhJ3tM2E0nJyyrUEjLJ1wq2WZqJ1mMlM0ZTyCrWOjhJ3tq2EZnJ1yM3E0LJywrPMjZT1Cq5OZhJ3tM2E0nJyarPMjBT04qmMZAT1CM5O0hJatrTZo7o3Q)

