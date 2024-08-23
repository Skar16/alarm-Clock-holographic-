# alarm-Clock-holographic-
This repo will include all technical and descriptive documentation of the university project "a alarm clock with holographic(spinning) threedimensional number display"


alarm clock spinning LED

# Electrical
Everything related to the electrical (and software/driver) part of the project
## spinning LED
* includes 4 led matrix (28mm x max. 60mm) for displaying 4 numberes
* matrix are inside of a test tube for protective reasons
* Angel of sight: 10° (2.5mm pitch, greetings from pythagoras)
  * 36 frames per rotation = 864 Hz  

### LEDs (Fabi & Torben)
* 0404 (RG)B LED
* max. 10 width (2.5mm pitch)
* max. 20 height (2.5mm pitch)
* charlie plexed

### PCB / Controller
* STM32F401 (84Mhz) + integrated IDE
* Input filter 

## Signal Transmit
* optimal: transmit nonencoded UART Signal 8N1
* induktiv or via bearings and contacts - schleifkontakte im kugellager
  * pre manufactured? (aliexpress?)
  * QI communication standard seems promising     



# Mechanis
Everything related to mechanical, moving parts like motor, gear etc.

## Motor
* 12V - 26W 
* PowerSupply (XT30)

## Belt and Gears
* timing belt(Zahnriehmen)
* gears printed or aliexpress (plastic)

## Motorcontroller (Fabi)
* recycle design



# Software
Everything related to the software part of the project

## LED Driver / Signal Processing
* compact written
* Speed, written from motor
* charlie plexed
* port mapping (LEDs)
* decode of UART Signal
    * somehow know which letter is displayed

* timing!!!


## Motor Driver
* maybe recycled
