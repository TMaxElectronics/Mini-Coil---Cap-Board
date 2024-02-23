# This file is part of Mini-Coil open source DRSSTC project
If you want to build one have a look at the entire project here: ...link TBD...
Are you building one right now and need info on it? Then keep reading :)

# How to build this part of the coil
This board is the dc-bus capacitance and probably the simplest one in the entire coil. 

Here's what you'll need to build it:
 - Soldering Iron
 - Solder (I suggest leaded solder if you don't have a powerful iron)
 - PCB Components (listed below)
 - at least one Cap Board PCB :)
 
# BOM (bill Of Material)
Since this board has such a small BOM I'll just list it here:

| Designator | Quantity | Description | Part Number / Order Number |
| ----------- | ----------- |
| C1-C16 | 16 | Electrolytic Capacitor 300V 1000uF (d-h-p=35-50-10)     | Epcos b43504-s3108-m3 |
| R1-R4 | 4 | High Power Resistor 47k 7W | SQMR747KJ |
| R5-R8 | 4 | THT Resistor 100k | MFR-25FRF52-100K |
| N1-N4 | 4 | Neon Indicator | A1A

These part requirements are not at all exact. If you have similar parts to any of these laying around or can get some other ones for cheaper go ahead :)
Just make sure that the ratings are sufficient and the footprint similar (especially of the caps).

**Note on the Capacitors:** These were available in bulk form a german Ebay seller at the time of designing this coil. If they are no longer sold then you are probably better of finding a cheaply available replacement. They were nothing special and only selected because I bought a bunch of them for cheap :)

**Word of warning on NOS or used Capacitors:** Buying used or new old stock capacitors is definetely not a bad bet if you want to save some money (thats what I did after all :P) but you want to be careful when first charging them. Electrolytic caps degenrate their oxide layer over time and if you immediately fully charge old caps they might actually short out internally. Look up "regenerating old capacitors" for a recommendation on how to charge old caps without destroying them. But the idea basically to jsut charge it to a low voltage, let it sit for a while, charge more, let it sit and so on and so on.

# Assembly notes
Most important: make sure to place the caps the right way around to avoid fireworks :P

Do not solder the caps first ;) I made that same mistake (because it just felt good immediately placing those many big caps :P) but trust me its a pain to populate the small tht resistors and the neon indicators.

If you didn't buy neon indicators or just don't like them for some reason you don't need to populate them. I added them as a safe and reliable indicator for "don't touch the coil, death cans still contain death".

# Testing
there's not really anything you can test on this board :) If you want to do it before putting the coil together you can re-generate the caps after assembly though (if neccessary).