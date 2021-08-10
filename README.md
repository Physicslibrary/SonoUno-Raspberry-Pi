# SonoUno-Raspberry-Pi

Note on building and exploring how SonoUno works on a Raspberry Pi

<img src="1.jpg" width="800">

The project is inspired by a BCC podcast about exploring the universe with sound.<br>

https://www.bbc.co.uk/programmes/p09mg44c

## Hardware

Tested on Raspberry Pi Raspberry Pi 4 Model B<br>

## Software

Raspberry Pi OS with desktop<br>
Release date: May 7th 2021<br>
Kernel version: 5.10<br>
Size: 1,180MB<br>

## Building SonoUno on a Raspberry Pi

Using "Installation" in<br>

https://github.com/sonoUnoTeam/sonoUno

as a starting point.<br>

Here is the author's note on building sonoUno on Raspberry Pi OS with desktop.<br>

In Terminal,<br>

sudo apt-get update

git clone https://github.com/sonoUnoTeam/sonoUno.git

cd sonoUno<br>

sudo apt install libsdl2-mixer-2.0-0 libsdl2-image-2.0-0 libsdl2-2.0-0 libsdl-ttf2.0-0 libgtk-3-dev<br>

python3 -m pip install -U wxPython<br>

(~80min for Pi4 to compile wxPython)<br>

python3 -m pip install pandas<br>

sudo apt-get install libatlas-base-dev<br>

python3 -m pip install oct2py<br>

sudo apt-get install octave<br>

pip3 install matplotlib<br>

cd sonoUno<br>

python3 sonoUno<br>

(some commands are "out of order" but that's what happen when one interactively, "pip3" or "apt-get" the missing software until "python3 sonoUno" works.)<br>

## Exploring how SonoUno works

## References

https://www.raspberrypi.org/products/raspberry-pi-4-model-b/

https://www.raspberrypi.org/software/operating-systems/

https://www.bbc.co.uk/programmes/p09mg44c

https://reinforceeu.eu/

https://reinforceeu.eu/events/webinars/how-help-scientists-gravitational-wave-noise-hunt

A pdf file about SonoUno from YouTube webinar "How to help scientists in the Gravitational Wave noise hunt"<br>

https://reinforceeu.eu/sites/default/files/2020-09/The%20use%20of%20sonification%20in%20REINFORCE%20-%C2%A0Beatriz%20Garcia.pdf

http://sion.frm.utn.edu.ar/sonoUno/

https://github.com/sonoUnoTeam/sonoUno


