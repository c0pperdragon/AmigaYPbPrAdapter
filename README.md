# Amiga YPbPr Adapter

To get the best possible image quality from a vintage Amiga (specifically Amiga 500) home computer.
The Amiga basically supports RGB output natively, but this standard is not suitable to directly
feed into a modern mid-range TV. The way to go with current TVs is component video (a.k.a YPbPr) that
has basically the same quality as RGB but uses a different way to encode everything.

As a matter of fact, the Y of YPbPr is just the (monochrome) luma signal together with sync, which is 
identical to the signal most Amiga computers (with the exception of the 600 and the 1200) already provide 
on their composite output port. 
So it is only necessary to create the suitable Pb and Pr signals to get full-blown YPbPr.

The adapter is intended to plug into the RGB video connector to produce the two missing signals.
Unluckily the RGB connector of the Amiga requires a female 23-pin SUB-D plug, and these connectors
are no longer in production. A 25-pin connector can be trimmed down to somehow fit, but this
requires quite some manual work and mass-production is out of the question. 

Nevertheless, I make everything open source in case someone else wants to build it.
  

