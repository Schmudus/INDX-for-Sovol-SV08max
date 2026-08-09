# INDX for Sovol SV08max
## Modification necessary to the Sovol SV08max
My printer has modificated electronics. The following may not be applicable to standard SV08max!

## Bed height
To fit INDX toolhead it is necessary to raise the bed about 12mm. I did this with 12mm silicon spacer (e.g. Creality use them) and put one washer under and over them. I glued the washer to the silicon and glued the part then to the SV08max frame (after lifting the aluminum plate). Loosen the 8 screws and lift the bed to the right side (cable is back right).
You will need some longer screws:
4 piece M5 x 55 (flathead)
4 piece M5 x 30 (flathead)

## 1515 extrusion for nozzle dock
To park/store the nozzles it is necessary to provide a 1515 extrusion in front of the printer. I made a simple, non-adjustable holder for it. It is mounted on the flying gantry.
The camera need to move away. Just unscrew it (one screw), pull the cable gently out of the right extrusion and place it in the back. There are 2 possible positions at the back gantry where already threads are placed. 

## X-axis limit switch
To use INDX it is necessary to find another limit switch position for X-Axis. The INDX toolhead have a plug for limit switch but (depending on your setup) not have any space to add aswitch.
Therefore I moved it to the right side of the gantry. 
I use a D2F-JO1F switch with a D2F to JST board (source: trianglelab).

## Nozzle offset determination
Nudge or camera is recommended while camera is already implemented in INDX macros.
To use nudge I made a holder for nudge which is screwed instread of the right handle in the printer. After determination the nozzle offsets you need to dismantle the holder.
It is necessary to print some spacer because of the changed bed height. The nudge plate should sit good fixed on the printer bed to avoid wrong measurement.

## Top riser
Thx to Clutch Kick for the design with smooth outet walls.
I did some changes for installation of INDX:
- Closed the original PTFE routing in the right back part
- Remake the back middle part:
  - 6 holes for PTFE routing and one bigger for CPAP hose (SV08max TopHat smooth middle back PTFE) 
  - same as before but with 6 openings for stainless spring steel 7.5x0.5mm (SV08max TopHat smooth middle back PTFE+spring steel) --> EDIT: It looks like it will be better to have the spring steel on the other side (below PTFE instead of above)
- Holder for the PTFE tube with spring steel 7.5x0.5mm (PTFE springsteel holder)

## Config files
Files moved to Klipper backup in: https://github.com/Schmudus/SV08max/tree/main/printer_data/config
Files and config are still in work but some parts can be used as example how it works.
Installed latest
- Kalico
- Axiscope
- Shake 'n' tune
- Sonar
- Timelapse
- LED effect
- INDX configuration files (INDX is implemented in Kalico, no installation necessary)

## Disclaimer
THE FILES IN THIS REPOSITORY ARE PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH 
THE FILES IN THIS REPOSITORY OR THE USE OR OTHER DEALINGS IN THE FILES IN THIS REPOSITORY.
THE FILES IN THIS REPOSITORY ARE OPEN SOURCE.


## Links
https://www.bondtech.se/indx-by-bondtech/ </br>
https://github.com/BondtechAB/INDX </br>
https://github.com/zruncho3d/nudge </br>
https://github.com/Sovol3d/SV08MAX </br>
https://oshwa.org/resources/open-source-hardware-definition/ </br>
https://www.printables.com/model/1456462-sv08max-riser-for-stock-enclosure-smooth-outer-wal </br>
https://github.com/nic335/Axiscope </br>
https://github.com/julianschill/klipper-led_effect </br>


