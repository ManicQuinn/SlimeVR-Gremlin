# Gremlin Trackers
A case design based on a [Stacked Smol-Slime](https://github.com/LyallUlric/Stacked-SmolSlime) layout, with a slide tray and a charging dock(Planned).

## Purchasing Guide

**Recommended Components**

| Component | Variation | Link |
| --- | --- | --- |
| nRF52840 SuperMini/ProMicro | N/A | https://www.aliexpress.com/item/1005007738886550.html?mp=1 |
| Tactile Button 3X4X2MM SMD 2-PIN | N/A | https://www.aliexpress.com/item/1005007004194449.html?mp=1 |
| 401230 3.7V 110mAh Battery | L0110 | https://www.aliexpress.com/item/714331867.html?mp=1 |
| IMU of Choice(Refer to Smol Documentation for compatibility) | N/A | https://docs.shinebright.dev/diy/smol-slime.html#tracker |
| nRF52840 Dongle (eByte(E104-BT5040U) or Nordic Semiconductor(PCA10059) or SuperMini) | N/A | N/A |
| 30mm Straps with Silicone | 30mm | https://www.aliexpress.com/item/1005003917576160.html?mp=1 |
> [!IMPORTANT]
> Purchase 30% more boards than needed to avoid extra shipping costs and time waiting on Dead on Arrival or boards that get damaged from assembly or soldering.

## Assembly Guide

**Stacked SmolSlime Tutorial** by **Lyall Ulric**

[![sddefault](https://github.com/user-attachments/assets/2ab7a9b1-e2d8-45b2-9de3-5c00a05b62f4)](https://youtu.be/qTmIfa_Asic)

> [!TIP]
> *Photo is a Embed Link*


## Photos
**Prototype 0.9.5**

*(Dimensions: 36.95mm x 38.64mm x 8.4mm)*

<p float="left">
  <img src="/photos/0.9.5/GremlinTrackers1.png" width="300" />
  <img src="/photos/0.9.5/GremlinTrackers2.png" width="300" /> 
  <img src="/photos/0.9.5/GremlinTrackers3.png" width="300" />
  <img src="/photos/0.9.5/GremlinTrackers4.png" width="300" />
  <img src="/photos/0.9.5/GremlinTrackers5.png" width="300" />
</p>

## To Do List:

- [X] Reverse clips. (Clips on Case)
- [X] ~~Simplify lid wedge into a sharp wedge and not what it is now with a flat side. (Don't worry, this is not confusing)~~ (This got too hard, so I gave up)
- [X] Get a prototype printed and sent to make measurement revisions, proving hard to do through others.
- [X] Remove charging hole on tray.
- [X] ~~Attempt a plug that closes the button when not pressed, same reasoning as #4.~~ (This requires knowledge of slicing the print, so on hold for now)
- [X] Add a lil standoff on the end of the lid to limit it at the end of the tray. (Added a standoff on battery side)
- [X] Reduce the thickness around the antenna.
- [X] Change slide tab design to reduce overhang print stress.
- [X] Increase tab strength. (0.05)
- [X] Increase vertical tolerances for NRF. (0.2)
- [X] Fix rocking issues on lid, slight design change required. (Tried only to reduce tolerances of tabs that push down on components, also added a standoff on battery side, finally redid the position of the top tab so we can have all tabs available)
- [X] ~~Fix button tolerance, seems to meld together.~~ (Irrelevant for due to redesign)
- [X] Add holes for soldering points on both case and lid. (0.8mm extrusions, needs more for the IMU on lid)
- [X] Simplify button compliant mechanism.
- [X] Double check lid tolerances with case.
- [X] Increase USB Hole height a lil
- [X] Increase height of case by maybe 0.1mm
- [X] Fix vertical(0.05mm) and horizontal extrusions on Case not matching up with extrusions of Tray. (Move sketches and Extrudes)
- [X] Fix Lid Extrusions to match Design.
- [X] Fix bottom not having a curve from last iteration
- [X] Redo Lid tabs, not satisfied with the click.
- [X] Figure out a fix for button falling off.
- [X] Change angles and measurements of strap loops to accommodate for the bottom curve.
- [X] Reduce tolerances of tray clips to fix them having too much give.
- [X] Optimize case design for lid.
- [X] Add parameters for certain measurements.
- [X] ~~Create a calibration cube.~~ (Not needed)
- [ ] Create a tray for a chest tracker.
- [X] Do a test print; Test Fragility of new strap loops, test the give of the tray/slide, test new button. (Brass 🩷)
- [ ] Work on aesthetics.

## Credit
| Contributor | Description | Link |
| --- | --- | --- |
| Brassflamingo and BrisIbis | A lot of help with Prototyping. | N/A |
| SlimeVR Team | Everything SlimeVR | https://github.com/SlimeVR |
| Sctanf | Smol-Slime Firmware and Hardware design. | https://github.com/SlimeVR/SlimeVR-Tracker-nRF |
| ShineBrightMeow | Smol-Slime Documentation | https://docs.shinebright.dev/diy/smol-slime.html |
| LyallUlric | Contributions to the stacked smol-slime branch. | https://github.com/LyallUlric/Stacked-SmolSlime |
