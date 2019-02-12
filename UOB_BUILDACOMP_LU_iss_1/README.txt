UOB BUILDACOMP LU iss 1 PCB build.

Additional build information

Contact: Craig Blackmore
Email: cb0094@my.bristol.ac.uk
Address: Merchant Venturers Building
Woodland Road
Bristol
United Kingdom
BS8 1UB

PCB Design Tool: KiCad

Description of files included in UOB_BUILDACOMP_LU_iss_1_order.zip:

./README.txt    This File

./gerb/   This directory contains the following gerber files for the design.

logicunit-F_Cu.gtl	Top Copper Layer 	(Layer 1)
logicunit-B_Cu.gbl	Bottom Copper Layer 	(Layer 2)
logicunit-F_Mask.gts	Top Solder Mask
logicunit-B_Mask.gbs	Bottom Solder Mask
logicunit-F_Paste.gtp	Top Solder Paste
logicunit-B_Paste.gtp	Back Solder Paste
logicunit-F_SilkS.gto	Top Silk Screen
logicunit-B_SilkS.gto	Back Silk Screen
logicunit-drl_map.pho	Gerber format Drill File (plated through holes)
logicunit-NPTH-drl_map.pho	Gerber format Drill File (non-plated through holes)
logicunit-Edge_Cuts.gbr	Edge Cuts

** It is acceptable for the holes marked "non-plated through hole" to be plated, if this aids manufacturing **


./drill

logicunit.drl	Excellon format drill file, plated holes - Decimal, absolute co-ordinates. Hole size is finished size.
logicunit-NPTH.drl	Excellon format drill file, non-plated holes (mechanical) - Decimal, absolute co-ordinates. Hole size is finished size.
logicunit-drl.rpt	Text drill size and number summary


./BOM

logicunit-BOM.csv	Excel format Bill of Materials


./XY/			XY Component position data in Excel format
logicunit-XY_Positions-F.Cu.csv    Front positions file (Assembly on front side only)

./netlist/      This directory contains the netlist files for equivalence checking and bare board test.

logicunit.net	Netlist (KiCad format)


./schematics Schematic in .pdf format

logicunit.pdf
