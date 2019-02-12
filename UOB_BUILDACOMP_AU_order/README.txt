UOB BUILDACOMP AU PCB build.

Additional build information

Contact: Craig Blackmore
Email: cb0094@my.bristol.ac.uk
Address: Merchant Venturers Building
Woodland Road
Bristol
United Kingdom
BS8 1UB

PCB Design Tool: KiCad

Description of files included in UOB_BUILDACOMP_AU_order.zip:

./README.txt	This File

./gerbers/	This directory contains the following gerber files for the design.

4bitAddSub-F_Cu.gtl	Top Copper Layer	(Layer 1)
4bitAddSub-B_Cu.gbl	Bottom Copper Layer	(Layer 2)
4bitAddSub-F_Mask.gts	Top Solder Mask
4bitAddSub-B_Mask.gbs	Bottom Solder Mask
4bitAddSub-F_Paste.gtp	Top Solder Paste
4bitAddSub-B_Paste.gbp	Bottom Solder Paste
4bitAddSub-F_SilkS.gto	Top Silk Screen
4bitAddSub-B_SilkS.gbo	Bottom Silk Screen
4bitAddSub-drl_map.pho	Gerber format Drill File	(plated through holes)
4bitAddSub-NPTH-drl_map.pho	Gerber format Drill File	(non-plated through holes)
4bitAddSub-Edge_Cuts.gbr	Gerber format edge cuts	(PCB outline)

** It is acceptable for the holes marked "non-plated through hole" to be plated, if this aids manufacturing **


./drills

4bitAddSub.drl	Excellon format drill file, plated holes - Decimal, absolute co-ordinates. Hole size is finished size.
4bitAddSub-NPTH.drl	Excellon format drill file, non-plated holes (mechanical) - Decimal, absolute co-ordinates. Hole size is finished size.
4bitAddSub-drl.rpt	Text drill size and number summary


./BOM

4bitAddSub-BOM.csv	CSV format Bill of Materials


./XY

4bitAddSub-F.Positions.csv	CSV format positions file (components present on front/top layer only)


./netlist

4bitAddSub.net	Netlist for equivalence checking and bare board test (KiCad format)


./schematics

4bitAddSub-Schematic.pdf PCB schematic in .pdf format for reference



