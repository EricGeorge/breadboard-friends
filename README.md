breadboard-friends
==================

A collection of cute breakout boards riding solderless breadboards, mostly for analog audio works

These PCB layouts and schematics are released under a Creative Commons cc-by-sa
3.0 license.

NOTE:  This repo has been forked from Mutable Instruments breadboard-friends and adds
1 new board - a MIDI IN/OUT breakout board.  It uses a similar design to the MIDI circuit in
Mutable Instrument Shruthi schematics.  It requires +5V power on VCC.  VEE is not 
connected.

BBF-MIDI Bill of Materials (BOM)

| Reference | Value | Part |
| ------------- | ------------- | ------------ |
| C1 | 0.1uF | 5mm ceramic cap |
| D1 | 1N4148 | Diode |
| J1 | MIDI IN | SDS-50J |
| J2 | MIDI OUT | SDS-50J |
| J3 | To Rx/From Tx | 2 pin male header |
| J4, J5 | Power headers | 10 pin DIL male header |
| R1, R2 | 220 Ω | 1% metal film resistor |
| R3 | 10k Ω | 1% metal film resistor |
| U1 | 6N137 | optical coupler 8-dip |