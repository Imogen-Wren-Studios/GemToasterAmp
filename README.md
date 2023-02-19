# GemToasterAmp
 9v to 12v Battery Powered Amp

 _LM386 Based power amp with JFET Preamp_

 - Quality of sound highly dependent on speaker & cab combo.
 
 ## 3D Model
 #### Iso
 ![image](https://user-images.githubusercontent.com/97303986/219975264-0416a19e-cfc4-4eef-a3ae-3caea3fa6e59.png) 
 #### Underside
 ![image](https://user-images.githubusercontent.com/97303986/219975292-bcfef8a9-9dc9-4e45-bd41-7526689ad503.png)
 #### Topside
 ![image](https://user-images.githubusercontent.com/97303986/219975322-cceffca0-5d27-470d-be27-a1bfb4f6e561.png)

 
 ## PCB Layout
 ![image](https://user-images.githubusercontent.com/97303986/219975145-c7bb9792-f08b-4527-ac55-0830714a7078.png)

 
 ## Schematic
 
 ![image](https://user-images.githubusercontent.com/97303986/219098777-c474740c-d59e-4d92-8f3e-428e28ce3c5c.png)
 
 
 
 ### JFET Selection
 
 _I thought there were some notes on this but I can't find them, the only other thing I had read says "Anything Goes". They used cheapo out of spec parts and they worked._
 
### Other Parts slection

Some parts can be more difficult to find or I just didnt have them in stock for my test build, so these are the values I used in my *working* build:
 
 3.9k Resistors - 15k in parallel with 5.1k
 4.3k Resistors - 15k in  parallel  with 6.2k
 
 
470n Capacitor - 390n Could put an additional 100n in parallel to get closer to marked value

15n Capacitor - 22n


## Revision 0 Issues:
- Power Amp control is backwards, but this control isnt that useable, on the origional project this was replaced with a trimpot anyway, so suggest mounting it back to front for a "set and forget" control, or replace with fixed value resistor.
   - Could also look into cutting traces between 2 and 3 - TODO
