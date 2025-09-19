# DTE LBM Files
This repo dedicates itself to serving the needs of the Lung Balloon Model subteam who aim to improve their file organization and version control

## The ZIP files in the PCB folder include KiCad 9.0:
- schematic
- PCB
- Gerber files

## Links:
- See all CAD/symbol/footprint sources in our active part file [here](https://docs.google.com/document/d/1QMjIAoFZjg54AbbEjMmA8GU2GEnOYeSXIRdQSNKbI4s/edit?tab=t.0)
- Info on [Mounting Holes](https://www.pcbway.com/blog/PCB_Basic_Information/What_are_Mounting_Holes_PCB_Knowledge_51332b83.html), and a [video](https://www.youtube.com/watch?v=pS7SrL-ZjmY&t=88s)
- Queen Mansy [video](https://mediasite.video.ufl.edu/Mediasite/Play/034c2cac9c494a558d50666e44f101571d) and DigiKey [video](https://youtu.be/vaCVh2SAZY4?si=QFfocP4VFCrLDv6F) for any PCB design questions
- [Manufacturer](https://www.allpcb.com/) of choice
- [Here](https://docs.google.com/document/d/1WyrrMa_ALmPAZvznJT0KnZH_fDL_DI7VsiZPKaXexkY/edit?usp=sharing) is a _very_ brief introduction to GitHub that has just enough info for our teams needs :3



Step-by-Step Installation
Open Arduino IDE Preferences: Go to File > Preferences in the Arduino IDE. 
Add Additional Board Manager URLs: In the Preferences window, find the field labeled "Additional Board Manager URLs" and paste the following URL into it: https://arduino.esp8266.com/stable/package_esp8266com_index.json. 
Open the Board Manager: Go to Tools > Board > Boards Manager. 
Install the ESP8266 Package: In the Boards Manager, search for "ESP8266" and click the "Install" button for the package named "ESP8266 by ESP8266 Community". 
Select Your Board: After the installation is complete, go back to Tools > Board and select your specific ESP8266 board from the newly listed "ESP8266 Modules" category. 
Install USB Drivers (if needed): If your computer doesn't recognize your ESP8266 board when you connect it, you may need to install the specific USB driver for your board. For example, many NodeMCU boards use the CP2102 or CH340 USB-to-serial chip, which requires its own driver. 

https://youtu.be/OC9wYhv6juM?si=9rztiDlW8fdKX69T
