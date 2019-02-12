UOB BUILDACOMP CLK PCB build issue 2

Additional build information

Contact: Craig Blackmore
Email: cb0094@my.bristol.ac.uk
Address: Merchant Venturers Building
Woodland Road
Bristol
United Kingdom
BS8 1UB

PCB Design Tool: KiCad

Description of files included in UOB_BUILDACOMP_CLK_order.zip:

./README.txt	This File

./gerber/	This directory contains the following gerber files for the design.

Clock-F_Cu.gtl	Top Copper Layer	(Layer 1)
Clock-B_Cu.gbl	Bottom Copper Layer	(Layer 2)
Clock-F_Mask.gts	Top Solder Mask
Clock-B_Mask.gbs	Bottom Solder Mask
Clock-F_Paste.gtp	Top Solder Paste
Clock-B_Paste.gbp	Bottom Solder Paste
Clock-F_SilkS.gto	Top Silk Screen
Clock-B_SilkS.gbo	Bottom Silk Screen
Clock-drl_map.pho	Gerber format Drill File	(plated through holes)
Clock-NPTH-drl_map.pho	Gerber format Drill File	(non-plated through holes)
Clock-Edge_Cuts.gbr	Gerber format edge cuts	(PCB outline)

** It is acceptable for the holes marked "non-plated through hole" to be plated, if this aids manufacturing **


./drill/

Clock.drl	Excellon format drill file, plated holes - Decimal, absolute co-ordinates. Hole size is finished size.
Clock-NPTH.drl	Excellon format drill file, non-plated holes (mechanical) - Decimal, absolute co-ordinates. Hole size is finished size.
Clock-drl.rpt	Text drill size and number summary


./XY/

Clock-XY_Positions-F.Cu.csv	CSV format positions file front side
Clock-XY_Positions-B.Cu.csv CSV format positions file back side


./BOM

Clock-BOM.csv	CSV format Bill of Materials


./netlist

Clock.net	Netlist for equivalence checking and bare board test (KiCad format)


./schematics

Clock-Schematic.pdf PCB schematic in .pdf format for reference



