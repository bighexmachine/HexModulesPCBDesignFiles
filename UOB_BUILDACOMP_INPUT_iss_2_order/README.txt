UOB BUILDACOMP INPUT iss 2 PCB build.

Additional build information

Contact: Craig Blackmore
Email: cb0094@my.bristol.ac.uk
Address: Merchant Venturers Building
Woodland Road
Bristol
United Kingdom
BS8 1UB

PCB Design Tool: KiCad

Description of files included in UOB_BUILDACOMP_INPUT_iss_2_order.zip:

./README.txt    This File

./gerb/   This directory contains the following gerber files for the design.

4bitInput-F_Cu.gtl	Top Copper Layer 	(Layer 1)
4bitInput-B_Cu.gbl	Bottom Copper Layer 	(Layer 2)
4bitInput-F_Mask.gts	Top Solder Mask
4bitInput-B_Mask.gbs	Bottom Solder Mask
4bitInput-F_Paste.gtp	Top Solder Paste
4bitInput-B_Paste.gbp	Back Solder Paste
4bitInput-F_SilkS.gto	Top Silk Screen
4bitInput-B_SilkS.gbo	Back Silk Screen
4bitInput-drl_map.pho	Gerber format Drill File (plated through holes)
4bitInput-NPTH-drl_map.pho   Gerber format Drill File (non-plated through holes)
4bitInput-Edge_Cuts.gbr Edge Cuts

** It is acceptable for the holes marked "non-plated through hole" to be plated, if this aids manufacturing **


./drill

4bitInput.drl	Excellon format drill file, plated holes - Decimal, absolute co-ordinates. Hole size is finished size.
4bitInput-NPTH.drl   Excellon format drill file, non-plated holes (mechanical) - Decimal, absolute co-ordinates. Hole size is finished size.
4bitInput-drl.rpt	Text drill size and number summary


./BOM

4bitInput-BOM.csv	Excel format Bill of Materials


./XY/			XY Coponent position data in Excel format
4bitInput-XY_Positions-F.Cu.csv    Front positions file
4bitInput-XY_Positions-B.Cu.csv    Back positions file

./netlist/      This directory contains the netlist files for equivalence checking and bare board test.

4bitInput.net	Netlist (KiCad format)


./schematics Schematic in .pdf format

4bitInput.pdf

