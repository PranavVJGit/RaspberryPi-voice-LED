# RaspberryPi-voice-LED
controlling  LED through Google voice using Raspberry Pi

In this project I have used Raspberry PI 4 4 GB RAM to control LED lights connected through GPIO using voice with Google Assistant services

here are the steps 

# 1. Build your own Raspberry Pi Google Assistant

https://pimylifeup.com/raspberry-pi-google-assistant/
This assistant will actively listen to your voice and respond to your queries. To set up your own Google Assistant, this tutoril will through how to test your audio setup, signing up for the Google Assistant API and also show you how to download and set up the actual Google Assistant examples. By the end of this tutorial, you should have a very capable virtual assistant operating on your Raspberry Pi.

# 2. Edit the Pushto talk file to make the voice assistant work on device command

Note that latest version of the Google assistant SDK 2.2.4 https://developers.google.com/assistant/sdk/overview
(a) does not provide auto wake word recognition 
(b) some of the control words "Traits" like "switch on" Switch off" are now reserved and cannot be easily used

to over come this challege I followed the hack provided by this youtube
https://www.youtube.com/watch?v=BernZK1LSB0


# 3 used GPIO Zero library to control the LEDs 
I used the latest library for LED control https://gpiozero.readthedocs.io/en/stable/ as incicated below
https://projects-static.raspberrypi.org/projects/physical-computing/ddf11cf76ef996ec5fe618e1aec76008bb4b2a96/en/images/led-gpio17.png

# 4 putting all together 
Here is the youtube link for the Demo
https://www.youtube.com/watch?v=JrjvX6_xVrg


