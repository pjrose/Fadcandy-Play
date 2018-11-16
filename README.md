Follow instructions here:
https://learn.adafruit.com/1500-neopixel-led-curtain-with-raspberry-pi-fadecandy/fadecandy-server-setup

Except us config json from this repository.



cd ~
wget http://download.processing.org/processing-3.4-linux-armv6hf.tgz
tar xvfz processing-3.4-linux-armv6hf.tgz
cd ~/processing-3.4/
DISPLAY=:0 ./processing-java --sketch=home/pi/fadecandy/examples/processing/grid8x8_orbits/grid8x8_orbits.pde --present
