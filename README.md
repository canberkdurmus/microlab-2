# Microlab 2
A minilab solution that is fully modular, 3D printable and open source.

<img src="image/0.png" alt="Microlab 2" height="400"/>
<img src="image/3.jpg" alt="Microlab 2" height="400"/>

# Why not 10" rack?
10" racks are beautiful, I built several for different use cases and I love them. But I needed something different:
* Something considerably smaller than common 10" racks and while it can support almost all devices supported by 10" format.
* Something square, so any panel/tray can be placed any side. To provide flexibility for cooling, cabling, HMI.
* Something fully 3D printable. Couple of PLA rolls are much cheaper than most 10" rack solutions. M3 screws are also much cheaper than M6 rack screws while looking more proportional and being able to support the weight of any equipment listed below.
* Something fun to design and build.

# Components

### Qucik Guide
- *Col:* The vertical columns with holes that holds M3 nuts and/or 8x3 magnets.
- *Cap:* The parts on top and botton that holds 4-columns together.
- *Tray:* The parts that hold various devices horizontally. 
- *Panel:* To cover rack slots vertically with various small tweaks like fans, screens, buttons, knobs or nothing.
- *Mini-Tray:* System to keep small devices like Raspberry Pi or 2.5" SATA drives. Has 7 mini slots in 3.5U of space while allowing air flow vertically or from behind.

| File Name | Status | Description/Notes |
|-|-|-| 
| Structure-Col-6U-dual-magnet | OK | Print 4 of these to get started |
| Structure-Cap-v2 | OK | Print 2 of these to get started |
| Structure-Col-Guard-6U | OK | [Optional] To keep the hex nuts from falling behind the columns|
| Structure-Feet-Round-10mm | NOT TESTED | [Optional] To raise the setup for bottom air intake configuration | 
| Structure-Feet-Round-15mm | NOT TESTED | [Optional] 15mm version of feet.|
| Structure-Mid-Extender | OK | [Optional] For the ones who ran out of space fast. Holds two sets of columns together vertically. |
| Mini-Frame-3.5U | OK | Part-1 of the frame to use with the mini trays. |
| Mini-Frame-3.5U-2 | OK | Part-2 of the frame to use with the mini trays. |
| Mini-Tray-0.5-Blank | OK | Blank panel for unused mini-frame slots.|
| Mini-Tray-0.5-RPi4 | OK | Mini tray for Raspberry Pi 4|
| Mini-Tray-0.5-RPi5 | NOT TESTED | Mini tray for Raspberry Pi 5| 
| Mini-Tray-0.5-SATA2.5-Closed | OK | Mini tray to mount a SATA 2.5" drive facing SATA port backwards. |
| Mini-Tray-0.5-SATA2.5 | OK | Mini tray to mount a SATA 2.5" drive exposing the SATA port. |
| Panel-0.5U-7x-Power-Switch | OK | Panel for 7 rectangular power switches. Most switch models fit tightly with no problems.|
| Panel-0.5U-Keystone8 | OK | Somehow managed to fit Keystone type patch prts in a 0.5U footprint. |
| Panel-0.5U-Solid | OK | Print this perforated please. |
| Panel-1U-8xKeystone | OK | The standard 1U version of the Keystone panel |
| Panel-1U-Button12mm | NOT TESTED | Connect a 12mm push button for any purpose |
| Panel-1U-fan-40x3 | NOT TESTED | 3x40mm fans for an active cooling solution even for 1U |
| Panel-1U-fan-40x2 | NOT TESTED | 2-fan version of the 1U 40mm fan panel |
| Panel-1U-fan-40x1 | NOT TESTED | Single fan version of the 1U 40mm fan panel |
| Panel-1U-Knob-7mm | NOT TESTED | To use with a rotary encoder or a potentiometer for more HMI options |
| Panel-1U-Mag-Button12mm | NOT TESTED | Magnetic version of the button panel |
| Panel-1U-Mag-fan-40x1 | NOT TESTED | Magnetic version of the 40mm single-fan panel |
| Panel-1U-Mag-fan-40x2 | NOT TESTED | Magnetic version of the 40mm dual-fan panel |
| Panel-1U-Mag-fan-40x3 | NOT TESTED | Magnetic version of the 40mm triple-fan panel |
| Panel-1U-Mag-Knob-7mm | NOT TESTED | Magnetic version of the rotary encoder/potentimeter panel |
| Panel-1U-Mag-Passthrough | OK | To feed various cables into the system while looking good and having easy access. |
| Panel-1U-Mag | OK | Magnetic 1U plain panel|
| Panel-1U-Solid-1xKeystone | OK | Single Keystone panel, mostly for feeding the WAN port from back/sides to inside. |
| Panel-1U-Mag-1xKeystone | OK | Magnetic single Keystone panel, mostly for feeding the WAN port from back/sides to inside. |
| Panel-1U-Solid | OK | Simple 1U panel, please print this perforated. |
| Panel-2U-fan-60x2 | NOT TESTED | Dual 60mm fans on 2U panel |
| Panel-2U-fan-60 | NOT TESTED | Single 60mm fan on 2U panel |
| Panel-2U-fan-80 | NOT TESTED | Single 80mm fan on 2U panel |
| Panel-2U-Mag-fan-60 | NOT TESTED | Magnetic version of the single 60mm fans on 2U panel |
| Panel-2U-Mag-fan-60x2 | NOT TESTED | Magnetic version of the dual 60mm fans on 2U panel |
| Panel-2U-Mag-fan-80 | NOT TESTED | Magnetic version of the single 80mm fans on 2U panel |
| Panel-2U-Mag | OK | Magnetic 2U panel, please print this perforated. |
| Panel-2U-Solid | OK | 2U panel, please print this perforated. |
| Panel-3U-Disp7-Top | OK | Compatible with 7" touch screen (like Waveshare or similar from AliExpress). The screen sticiks out a bit because can't fit in between the columns. |
| Panel-3U-Disp7-Bottom | OK | The other half of the 7" touch screen panel |
| Panel-3U-Fan-120 | OK | 120mm PC fan on 3U panel |
| Panel-3U-Mag-Fan-120 | OK | 120mm PC fan on magnetic 3U panel |
| Panel-3U-Mag | OK | Magnetic 3U panel, please print this perforated. |
| Panel-3U-Solid | OK | 3U panel, please print this perforated. |
| Panel-4U-Mag | OK | Magnetic 4U panel, please print this perforated. |
| Panel-4U-Solid | OK | 4U panel, please print this perforated. |
| Top-Panel-Fan-120 | OK | 120mm PC fan on top exhaust (or bottom intake) for vertical air flow configuration. |
| Top-Panel-Slots | OK | Top/bottom panel that allows air flow without perforated print. |
| Top-Panel-Solid | OK | Please print this perforated for air flow. | 
| Tray-0.5U-RPi4-SATA | OK | Tray for Raspberry Pi 4 and a 2.5" SATA drive. |
| Tray-0.5U-RPi4 | OK | Tray for Raspberry Pi 4. |
| Tray-0.5U-RPi4x2 | OK | Tray for dual Raspberry Pi 4. |
| Tray-0.5U-RPi5 | NOT TESTED | Tray for Raspberry Pi 5. |
| Tray-0.5U-RPi5x2 | NOT TESTED | Tray for dual Raspberry Pi 5. |
| Tray-1.5U-SFX-L | OK | Tray to keep SFX/SFX-L PSU |
| Tray-1U-GMKTec-G3 | OK | Tray for GMKTec G3 (Plus) Intel N100 mini PC. I removed the top panel of the mini PC to have a satisfying fit into 2U. You can keep the top panel and have the upper 0.5U panel empty/compatible. The mini PC can be mounted facing inside or outside. Please use the little screws from the box to fix the mini PC to the tray. |
| Tray-1U-Switch-Netgear-GS308 | NOT TESTED | Tray for Netgear 8-port gigabit switch, print on its face please. |
| Tray-1U-Switch-TPLink-TLSG105 | OK | Tray for TP-Link 5-port gigabit switch, print on its face please. |
| Tray-1U-Switch-TPLink-TLSG108 | OK | Tray for TP-Link 8-port gigabit switch, print on its face please. |
| Tray-0.5U-Switch-Tenda-SG108 | OK | Tray for Tenda SG108 8-port gigabit network switch. The outer shell of the swtich should be removed. In return, it takes up only 0.5U space and very little depth. |
| Tray-0.5U-Template-Starter | N/A | Quickstart to a new 0.5U tray design |
| Tray-1U-Template-Starter | N/A | Quickstart to a new 1U tray design |
| Tray-1U-Template-Starter-2 | N/A | Quickstart with another approach to a new 1U tray design |
| Tray-2U-X300 | OK | Tray for ASRock DeskMini X300 (and X600) barebone PC. |
| Tray-2U-X300-Acc | OK | Small but needed additional part for ASRock X300/|
| Extension-ITX-1U | NOT TESTED | This part allows you to put a MiniITX board on top of the Microlab. It's mainly intended for N100 MiniITX boards with many SATA ports from Aliexpress but any board should work fine. Select the height of the extension depending on the needed additional space and keep your cooler height in mind. Any panel/tray/cap should be compatible with the columns here. |
| Extension-ITX-2U | NOT TESTED | See: Extension-ITX-1U |
| Extension-ITX-3U | NOT TESTED | See: Extension-ITX-1U |
| Extension-ITX-4U | NOT TESTED | See: Extension-ITX-1U |
| Extension-ITX-5U | NOT TESTED | See: Extension-ITX-1U |

# Materials
* M3x10 (or M3x12) screws and nuts (How many: Min 32 screw-nut pairs if all side panels are magnetic, 112 pairs for full screw-nut 6U build, I use ~160-180 pairs for my 6+4 extended setup combined with magnetic panels)
* [Optional] 8x3mm Magnets for magnetic panels, 4 magnets/1U

# Notes
* All side panels have the same dimension standards, so any panel/tray can be attached to any side. Just make sure to put magnets/nuts behind the needed spots before assembling everything for a better general use experience.
* Make sure all magnets have consistent polarity, so any magnetic panel can be placed at anywhere with magnets.
* Please glue your magnets to places and wait for glue to dry before attaching magnetic panels/trays.
* Raspberry Pi 3 users can use Pi 5 trays with no problems. The front face is virtually identical. Also, ASUS Tinkerboard 2 is tested and fully compatible.
* Technically this system can hold a Mini-ITX motherboard with numerous 2.5" drives in mini-tray(s) and a SFX/SFX-L PSU.
* Cabling for the power switches can be tricky for Raspberry Pi. Powering from GPIO can be risky due to by-passing the 5V regulator.
* The whole thing can be used horizontally. Just assemble the feet to the cap screw points and plan your cooling accordingly.

# TODO
- [ ] 3.5" HDD tray
- [ ] PCI card support for ITX extension (maybe as a tray to use with PCI riser cable)
- [ ] Trays for common 2.5G network switch models 
- [ ] Trays for more mini PC models
- [ ] M3 insert version for columns
- [ ] Handles to carry it around
