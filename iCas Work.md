Lab Protocol
----
iCas Work
----
iCas-sgEGFP Work
----

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
	7. Pipette 80 ul cells onto LB Agar plates, containing 100 ug/ml ampicillin, spread the mixture and grow in an incubator overnight at 37 degree.


