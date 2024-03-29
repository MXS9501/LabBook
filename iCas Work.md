iCas Work
---
Author: Jiahao Cui
Date: 20210310
---
iCas-sgRNA Work with Ligation, Cell Transfection, FACS Sorting, 4-HT Treatment.
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
	5. Run the content on the gel, 2x20 ul, 1 % agarose gel, 100V, 90 min, BplI digestion should result in 13048 bp.

# Annealing of sgEGFP for duplexes
	1. Make Mix
		-100 uM Sense Oligo,sgEGFP, 1 ul
		-100 uM Antisense Oligo, sgEGFP, 1 ul
		-10x T4 Ligase Buffer, 1 ul
		-T4 PNK, 1 ul
		-DEPC Water, 6 ul
		Total in 10 ul
	2. Short vortex and spin down.
	3.Set up the following reaction condition in a thermal cycler: 37 degree for 30 min, 65 degree for 20 min, ramp down to 4 degree at 6 degree per min, and hold at 4 degree.

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

# Double Enzyme Check to the iCas backbone
	1. Digest the sequence-correct plasmid with XbaI and SnaBbI for 3 hours
	2. Run 1% Agarose Gel, with 100 V for 90 min.

# Maxi Prep
	1. Choose the right-sequence with right Backbone colony
	2. Small culture in 5 mL LB Broth with antibiotic for overnight.
	3. Transfer the 5 ml into 200 mL LB Broth with antibiotics, incubate the bacteria until OD600=0.8
	4. Spin down all bacteria with 8500 rpm, 15 min.
	5. Do Maxi Prep following Kit protocol.
	6. Elute DNA with DEPC water for 300~400 ul.
	note: centrifugation is suggested after getting cell lysis and incubation with buffer.

# Mammalian cell culture (adherent cells, HeLa S3)
	Note: All Reagent which is used for tissue culture shall be heated in 37 degree water-bath first.
	Note: FBS should be melt in 4 degree overnight, before aliquot into 50 mL tubes, FBS should be inactivated under 55 degree.
	Note: Typsin-EDTA should be melt in 4 degree. Before adding into plate, do pre-heat at RT.
	1. Thaw 1 ml Hela S3 with 37 degree water bath, transfer the cell into 15 ml centrifuge tube with 2 ml PBS.
	2. Spin down the cell with 1000 rpm, 1 min.
	3. Discard the supernatant, re-suspend the cell using 1 mL DMEM with 10% FBS.
	4. Transfer the cells onto 100 mm dish (14 ml DMEM inside already) with 10% FBS in DMEM, recover overnight in 37°C, 5% CO2
	5. Passage the cell while they are attached to walls and confluent. 
	6. Examine under a microscope to make sure they are well incubated.
	7. Aspirate the media and wash by 10 mL PBS. Then aspirate the PBS. Do this step twice.
	8. Add 2 ml 0.25% trypsin-EDTA and swirl the plate to distribute evenly. Incubate at 37C, 1 minutes (do not over or under-trypsinize, check by gently bumping the plate on the table and then look at the floating cells under the microscope).
	9. Add 4 mL DMEM with FBS to neutralize trypsin. 
	10. Pipette the cells softly to dissociate the cell clumps into single cells.
	11. Transfer 2 mL (6 mL to total) cells into a new dish (this represent a 1:3 split; higher or lower splitting ratios may be needed).
	12. Incubate at 37C overnight, next day check the situation.

# Transfection using Lipofectamine 2000.
	Note: ALl reagent should be prepared well before starting this part.
	1. Seed cells to be 70%-90% confluent at transfection
	2. Dilute Lipofectamine Reagent in Opti-MEM Medium, add 30 ul Lipo2000 into 500 ul pure DMEM
	3. Dilute DNA in Opti-MEM Medium, add 14 ug into 500 pure DMEM
	4. Mix Diluted DNA and Diluted Lipo2000, 1:1
	5. Incubate for 5 minutes at RT
	6. Add DNA -Lipo2000 complex to cells.
	7. Incubate cells for 1-3 days at 37 degree.


# FACS Checking OFP
	1.
# 4-HT Treatment
	1.
