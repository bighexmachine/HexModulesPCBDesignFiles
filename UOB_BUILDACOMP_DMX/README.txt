UOB BUILDACOMP DMX PCB build.

Additional build information

Contact: Craig Blackmore
Email: cb0094@my.bristol.ac.uk
Address: Merchant Venturers Building
Woodland Road
Bristol
United Kingdom
BS8 1UB

PCB Design Tool: KiCad

Description of files included in UOB_BUILDACOMP_DMX_order.zip:

./README.txt    This File

./gerb/   This directory contains the following gerber files for the design.

4bit4waydemux-F_Cu.gtl	Top Copper Layer 	(Layer 1)
4bit4waydemux-B_Cu.gbl	Bottom Copper Layer 	(Layer 2)
4bit4waydemux-F_Mask.gts	Top Solder Mask
4bit4waydemux-B_Mask.gbs	Bottom Solder Mask
4bit4waydemux-F_Paste.gtp	Top Solder Paste
4bit4waydemux-B_Paste.gtp	Back Solder Paste
4bit4waydemux-F_SilkS.gto	Top Silk Screen
4bit4waydemux-B_SilkS.gto	Back Silk Screen
4bit4waydemux-drl_map.pho	Gerber format Drill File (plated through holes)
4bit4waydemux-NPTH-drl_map.pho	Gerber format Drill File (non-plated through holes)
4bit4waydemux-Edge_Cuts.gbr	Edge Cuts

** It is acceptable for the holes marked "non-plated through hole" to be plated, if this aids manufacturing **


./drill

4bit4waydemux.drl	Excellon format drill file, plated holes - Decimal, absolute co-ordinates. Hole size is finished size.
4bit4waydemux-NPTH.drl   Excellon format drill file, non-plated holes (mechanical) - Decimal, absolute co-ordinates. Hole size is finished size.
4bit4waydemux-drl.rpt	Text drill size and number summary


./BOM

4bit4waydemux-BOM.csv	Excel format Bill of Materials


./XY/			XY Component position data in Excel format
4bit4waydemux-XY_Positions-F.Cu.csv    Front positions file (Assembly on front side only)

./netlist/      This directory contains the netlist files for equivalence checking and bare board test.

4bit4waydemux.net	Netlist (KiCad format)


./schematics Schematic in .pdf format

4bit4waydemux.pdf
