# Mahjong to JAMMA adapter

Enables you to play Mahjong games in a JAMMA setup like arcade cabinet or supergun. 
This has 3.96mm pitch for the mahjong side pads which is same as with JAMMA. Note that some Mahjong games use 4mm pitch.
Be sure to check that the adapter lines with the game pcb pads correctly.


The main Mahjong controls can be extended with the 6- and 5-pin connectors. 
Additional 4-pin connector is also available for wiring coin, test and service buttons with GND.
Connector pins are with 2.5mm pitch, but 2.54mm should also work.


The -5V requirement and GND to "JAMMA Spk-" can be bridged if needed.


Audio section can be wired with a switch to change between connecting "JAMMA Spk-" to "Mahjong Spk-" or to GND.
Be sure what connections your game(s) require. For example Hot Gimmick needs the "JAMMA Spk-" to be connected to "Mahjong Spk-" or there won't be any sound.
Connecting this wrong can cause sound to be missing, distorted, low volume and possibly components overheating.


Mahjong pinout that was followed when designing this
![Alt text](../mahjong_pinout.jpg?raw=true "Mahjong pinout img")

Bare pcb
![Alt text](mahjong_jamma_adapter_bare.jpg?raw=true "Bare pcb img")

Control panel poulated
![Alt text](mahjong_jamma_adapter.jpg?raw=true "Adapter populated img")