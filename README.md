# hbprotocol

hbprotocol defines and implements a low level protocol shared between a few different hoverboard repositories. e.g. [ours](https://github.com/bipropellant/hoverboard-firmware)

It features two facets

* a reliable machine orientated binary protocol for machine control purposes.
* An ASCII orientated protocol for general control/experimentation by a human.

Both protocols may be active at the same time on the same serial line.

See Wiki for more detail