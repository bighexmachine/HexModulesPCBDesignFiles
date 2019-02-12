UOB BUILDACOMP RAM PCB build. Iss 2

Additional build information

Contact: Craig Blackmore
Email: cb0094@my.bristol.ac.uk
Address: Merchant Venturers Building
Woodland Road
Bristol
United Kingdom
BS8 1UB

PCB Design Tool: KiCad

Description of files included in UOB_BUILDACOMP_RAM_order.zip:

./README.txt    This File

./gerb/   This directory contains the following gerber files for the design.

RAM-F_Cu.gtl	Top Copper Layer 	(Layer 1)
RAM-B_Cu.gbl	Bottom Copper Layer 	(Layer 2)
RAM-F_Mask.gts	Top Solder Mask
RAM-B_Mask.gbs	Bottom Solder Mask
RAM-F_Paste.gtp	Top Solder Paste
RAM-B_Paste.gtp	Back Solder Paste
RAM-F_SilkS.gto	Top Silk Screen
RAM-B_SilkS.gto	Back Silk Screen
RAM-drl_map.pho	Gerber format Drill File (plated through holes)
RAM-NPTH-drl_map.pho	Gerber format Drill File (non-plated through holes)
RAM-Edge_Cuts.gbr	Edge Cuts

** It is acceptable for the holes marked "non-plated through hole" to be plated, if this aids manufacturing **


./drill

RAM.drl	Excellon format drill file, plated holes - Decimal, absolute co-ordinates. Hole size is finished size.
RAM-NPTH.drl   Excellon format drill file, non-plated holes (mechanical) - Decimal, absolute co-ordinates. Hole size is finished size.
RAM-drl.rpt	Text drill size and number summary


./BOM

RAM-BOM.csv	Excel format Bill of Materials


./XY/			XY Component position data in Excel format
RAM-XY_Positions-F.Cu.csv    Front positions file (Assembly on front side only)

./netlist/      This directory contains the netlist files for equivalence checking and bare board test.

RAM.net	Netlist (KiCad format)


./schematics Schematic in .pdf format

RAM.pdf
