UOB BUILDACOMP I2C iss1 PCB build.

Additional build information

Contact: Simon Hollis
Email: simon@cs.bristol.ac.uk
Address: Merchant Venturers Building
Woodland Road
Bristol
United Kingdom
BS8 1UB

PCB Design Tool: KiCad

Description of files included in UOB_BUILDACOMP_FOUT_iss_2.zip:

./README.txt    This File

./gerb/   This directory contains the following gerber files for the design.

I2C-F_Cu.gtl	Top Copper Layer 	(Layer 1)
I2C-B_Cu.gbl	Bottom Copper Layer 	(Layer 2)
I2C-F_Mask.gts	Top Solder Mask
I2C-B_Mask.gbs	Bottom Solder Mask
I2C-F_Paste.gtp	Top Solder Paste
I2C-B_Paste.gtp	Back Solder Paste
I2C-F_SilkS.gto	Top Silk Screen
I2C-B_SilkS.gto	Back Silk Screen
I2C-drl_map.pho	Gerber format Drill File (plated through holes)
I2C-NPTH-drl_map.pho   Gerber format Drill File (non-plated through holes)
I2C-Edge_Cuts.gbr Edge Cuts

** It is acceptable for the holes marked "non-plated through hole" to be plated, if this aids manufacturing **


./drill

I2C.drl	Excellon format drill file, plated holes - Decimal, absolute co-ordinates. Hole size is finished size.
I2C-NPTH.drl   Excellon format drill file, non-plated holes (mechanical) - Decimal, absolute co-ordinates. Hole size is finished size.
I2C-drl.rpt	Text drill size and number summary


./BOM

I2C-BOM.csv	Excel format Bill of Materials


./XY/			XY Coponent position data in Excel format
I2C-XY-F.Cu.csv    Front positions file


./netlist/      This directory contains the netlist files for equivalence checking and bare board test.

I2C.net	Netlist (KiCad format)


./schematics Schematic in .pdf format

I2C.pdf

