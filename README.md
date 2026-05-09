# INDX for Sovol SV08max
## The files are preliminary because INDX is not yet delivered. There will be most likely modification after/during installation.
## Modification necessary to the Sovol SV08max
My printer has modificated electronics. The following may not be applicable to standard SV08max!

## 1515 extrusion for nozzle dock
To park/store the nozzles it is necessary to provide a 1515 extrusion in front of the printer. I made a simple, non-adjustable holder for it. It is mounted on the flying gantry.
The camera need to move away. Just unscrew it (one screw), pull the cable gently out of the right extrusion and place it in the back. There are 2 possible positions at the back gantry where already threads are placed. 

## X-axis limit switch
To use INDX it is necessary to find another limit switch position for X-Axis. The INDX toolhead have a plug for limit switch but (depending on your setup) not have any space to add aswitch.
Therefore I moved it to the right side of the gantry. 
I use a D2F-JO1F switch with a D2F to JST board (source: trianglelab).

## Nozzle offset determination
It is recomended to use nudge. To use it I made a holder for nudge which is screwed instread of the right handle in the printer. After determination the nozzle offsets you need to dismantle the holder.

## Top riser
Thx to Clutch Kick for the design with smooth outet walls.
I did some changes for installation of INDX:
- Closed the original PTFE routing in the right back part
- Remake the back middle part:
  - 6 holes for PTFE routing and one bigger for CPAP hose
  - same as before but with 6 openings for stainless spring steel 7.5x0.5mm (SV08max TopHat smooth middle back PTFE+spring steel)
- Holder for the PTFE tube with spring steel 7.5x0.5mm

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


