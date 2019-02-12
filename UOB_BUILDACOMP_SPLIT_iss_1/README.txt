UOB BUILDACOMP SPLIT iss 1 PCB build.

Additional build information

Contact: Craig Blackmore
Email: cb0094@my.bristol.ac.uk
Address: Merchant Venturers Building
Woodland Road
Bristol
United Kingdom
BS8 1UB

PCB Design Tool: KiCad

Description of files included in UOB_BUILDACOMP_SPLIT_iss_1_order.zip:

./README.txt    This File

./gerb/   This directory contains the following gerber files for the design.

split-F_Cu.gtl	Top Copper Layer 	(Layer 1)
split-B_Cu.gbl	Bottom Copper Layer 	(Layer 2)
split-F_Mask.gts	Top Solder Mask
split-B_Mask.gbs	Bottom Solder Mask
split-F_Paste.gtp	Top Solder Paste
split-B_Paste.gtp	Back Solder Paste
split-F_SilkS.gto	Top Silk Screen
split-B_SilkS.gto	Back Silk Screen
split-drl_map.pho	Gerber format Drill File (plated through holes)
split-NPTH-drl_map.pho	Gerber format Drill File (non-plated through holes)
split-Edge_Cuts.gbr	Edge Cuts

** It is acceptable for the holes marked "non-plated through hole" to be plated, if this aids manufacturing **


./drill

split.drl	Excellon format drill file, plated holes - Decimal, absolute co-ordinates. Hole size is finished size.
split-NPTH.drl   Excellon format drill file, non-plated holes (mechanical) - Decimal, absolute co-ordinates. Hole size is finished size.
split-drl.rpt	Text drill size and number summary


./BOM

split-BOM.csv	Excel format Bill of Materials


./XY/			XY Component position data in Excel format
split-XY_Positions-F.Cu.csv    Front positions file (assembly on front side only)
** NOTE: This board has no automatically placed components **

./netlist/      This directory contains the netlist files for equivalence checking and bare board test.

split.net	Netlist (KiCad format)


./schematics Schematic in .pdf format

split.pdf

