Lab Protocol>>>>Project: iCas Work
---
Author: Jiahao Cui>>>>Date: 20200915
---
iCas-sgEGFP Work
---
# iCas plasmid extraction
	1. Small culture from glycerol stock, tube number #84232, using 5 ml with 5 ul ampicillin, overnight, 37 degree
	2. Transfer 5 ml to 15 ml LB broth, 20 ml in total, keep culturing until become disence.
	3. Collect the bacteria with 8500 rpm, 10 min.
	4. Using QIAGEN mini-prep extraction kit to isolate iCas plasmid.

# Linearizion of iCas vector
	1. prepare the following digestion mix:
		- Isolated iCas vector, 2 ug
		- FastDigest BplI, 2 ul
		- 20x SAM, 2 ul
		- 10x FastDigest buffer, 4 ul
		- Water(nuclease-free), add up to 40 ul
	2. Mix Gentle and spin down
	3. Incubate the reaction for 3 hours at 37 degree.
	4. Perform a dephosphorylation step by adding 2µl antarctic shrimp phosphatase to the reaction and incubate for 30 minutes at 37°C.
	5. Run the content on the gel, 2x20 ul, 0.8% agarose gel, 100V, 90 min, BplI digestion should result in 13048 bp.

# Annealing of sgEGFP for duplexes
	1. Make Mix
		-100 uM Sense Oligo,sgEGFP, 1 ul
		-100 uM Antisense Oligo, sgEGFP, 1 ul
		-10x T4 Ligase Buffer, 1 ul
		-T4 PNK, 1 ul
		-DEPC Water, 6 ul
		Total in 10 ul
	2. Short vortex and spin down.
	3.Set up the following reacrion condition in a thermal cycler: 37 degree for 30 min, 65 degree for 20 min, ramp down to 4 degree at 6 degree per min, and hold at 4 degree.

# Cloning sgEGFP into iCas vector
	1. Dilute the annealed oligos 1:100, e.g., add 2 ul annealed oligos to 198 ul water
	2. Ligate annealed sgEGFP oligos into the iCas vector. In a PCR tube, set up the following reaction:
		-Linear iCas Vector, 50 ng
		-Diluted annealed oligos, 1 ul
		-10x T4 Ligase Buffer, 1 ul
		-T4 DNA ligase, 1 ul
		-DEPC water, add up to 10 ul
	3. Set up controls
		-No Insert, without gRNA oligos
		-No Ligase, without T4 DNA ligase
		-No Vector, without linear iCas vector
	4. Incubate the reaction overnight at 16 degree in a thermocycler.

# Bacteria Transformation
	1. Thaw four tubes of competent cells on ice, super Stbl3.
	2. Add 6 ul per ligation mix to 50 ul Competent cell.
	3. Incubate competent cells mix on ice for 30 min.
	4. Heat shock competent cells at 42 degree for 90 sec.
	5. Incubate Mix on ice for 3 min.
	6. Add 250 ul LB Broth into tube and incubate at 37 degree for 45 min.
	7. Spin down the bacteria at 6500 rpm, 1 min.
	8. Discard 200 ul supernatant and re-suspend the pellet with 100 ul remaining liquid.
	9. Spread the 100 ul Mixture and grow in an incubator overnight at 37 degree.

# Identification of correctly Cloned Plasmid by Colony PCR and Miniprep
	1.Set a Backup LB Agar (containing Ampicillin), and linear at the bottom of dish into 12 sections.
	2.Set a PCR mix (Each Tube):
		-Takara Taq (5U/ul), 0.25 ul
		-10X PCR Buffer (Mg++ plus), 5 ul
		-dNTP, 4 ul
		-Forward Primer (sgEGFP-Forward, 10 uM), 2 ul
		-Reverse Primer (M13-Reverse, 10 uM), 2 ul 
		-ddH2O to 50 ul

		OR Using PCR Master Mix (Sangon or YEASEN Company)
		-Forward Primer (sgEGFP-Forward, 10 uM), 2 ul
		-Reverse Primer (M13-Reverse, 10 uM), 2 ul 
		- PCR Master Mix, 25 ul
		-ddH2O to 50 ul
	3. Pick colonies randomly present on the agar plate using a 10 u pipette tip, before swiping it in the PCR tube, inoculate the tip on the Backup LB Agar 	plate softly. (Mark the orders clearly, e.g. 1# on the plate, also 1# on the tube).
	4. Set PCR reaction condition:
		-Initial denaturation, 95 degree, 5 min.
		-30 cycles,	95 degree, 30 sec
						    60 degree, 30 sec
						    72 degree, 30 sec/Kb
		-Final Extension, 72 degree, 10 min
		-Hold at 4 degree.
	5. Run all reactions out on 0.8 % agarose gel. Visualize in a gel imaging system.
	6. Inoculate the positive colonies in 5 ml LB Broth with ampicillin, for overnight.
	7. make the Glycerol Stock and isolate the plasmid using a miniprep kit.




