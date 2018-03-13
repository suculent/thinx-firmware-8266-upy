# thinx-firmware-8266-upy

THiNX ESP8266 Vanilla Firmware for Micropython

Can be assembled and managed by [Remote Things Management](https://rtm.thinx.cloud) based on [THiNX OpenSource IoT platform](https://thinx.cloud).

Because this firmware does not feature captive portal yet, it's important to set `THINX_ENV_SSID` and `THINX_ENV_PASS` or similar environment variables in order to inject your WiFi credentials to the device.

Fallback to WPS is possible, but it's not considered very secure.
