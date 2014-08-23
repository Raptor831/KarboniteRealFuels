KarboniteRealFuels
==================

So you want both Karbonite and Real Fuels? Here's a set of configs to enable the Karbonite converters and distillers to produce proper fuels for you. You'll need Real Fuels and Karbonite installed (obviously) as well as ModuleManager.

Installation
------------

Place the FalconTech folder in your GameData folder. If you already have a FalconTech folder, simply add the contents to your current /GameData/FalconTech/ folder, overwriting the old contents as needed.

Details
-------

The configs change a few things:

The density of Karbonite is reduced by a fifth to match the other RF fuels.
The amount of karbonite other parts hold is increased by 5. (So the same mass is still in each part)
The converter produces the more volatile fuels (LH2, LOX, Kerosene, etc).
The distillers produce the less volatile fuels (Hydrazine, HTP, Methane, etc)


I "created" a chemical formula for karbonite, which ended up being CH4NO2. Based on that formula, I did some chemistry to figure out what amounts of various fuels would come out. So, 1 molecule of karbonite after conversion produces 1 molecule of methane (CH4) and 1 molecule of LOX (O2). All of the units/masses should be "correct". And, any fuels that could not come from this (such as He) are not included. Most of my data came from Wikipedia.

Only one fuel comes out at a time. I had previously worked out multiple fuels per conversion, but it seemed overly complicated. Plus, the default RF config for Kethane does one fuel at a time as well, so I figured I'd follow that. Normal Karbonite fuel-flow rules apply, so double check your fuel lines and connections.

License
-------

Configs released under the CC Attribution-ShareAlike 4.0 International License.
