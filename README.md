# shutter
Raspberry shutter/dither (PHD2) script to control exposures and dithering in astro photography

The script shutter.py is intended to be run on a linux system on Raspberries.

It uses relais or other switches connected to the GPIOs to control the shutter of a camera.

It uses two relais and mimics the focus -> release sequence but could likely work with a single relais leaving out the focus contact or closing focus and release contacts at the same time.

It is possible to give the exact exposure time and pause sequence and multiplicators to keep the camera busy throughout the night.

In addition it is possible to connect to a running PHD2 Server to trigger dithering between the shots.

# SHUTTER SEQUENCE:

TODO: an example

# DITHERING with PHD2 between the shots

TODO: an example
