Lab Protocol
----
iCas Work
----
iCas-sgEGFP Work
----

# iCas plasmid extraction
	1. Small culture from glycerol stock, tube number #84232, using 5 ml with 5 ul ampcillin, overnight, 37 degree
	2. Transfer 5 ml to 15 ml LB broth, 20 ml in total, keep cultureing until become disence.
	3. Collect the becteria with 8500 rpm, 10 min.
	4. Using QIAGEN mini-prep extraction kit to isolate iCas plasmid.

# Linearization of iCas vector
	1. prepare the following digestioin mix:
		- Isolated iCas vector, 2 ug
		- FastDigest BplI, 2 ul
		- 20x SAM, 2 ul
		- 10x FastDigest buffer, 4 ul
		- Water(nuclease-free), add up to 40 ul
	2. Mix Gentle and spin down
	3. Incubate the reaction for 3 hours ar 37 degree.
	4. Perform a dephosphorylation step by adding 2µl antarctic shrimp phosphatase to the reaction and incubate for 30 minutes at 37°C.
	5. Run the content on the gel, 2x20 ul, 0.8% agarose gel, 100V, 90 min, BplI digestion should result in 13048 bp.

# Annealing of sgEGFP for dulplexes
	1. Make Mix
		-100 uM Sense Oligo,sgEGFP, 1 ul
		-100 uM Aitisense Oligo, sgEGFP, 1 ul
		-10x T4 Ligase Buffer, 1 ul
		-T4 PNK, 1 ul
		-DEPC Waster, 6 ul
		Total in 10 ul
	2. Short vortex and spin down.
	3.Set up the following reacrion condition in a thermal cycler: 37 degree for 30 min, 95 degree for 5 min, ramp down to 25 degree at 6 degree per min, and hold at 25 degree.

# Cloning sgEGFP into iCas vector
	1. Dillute the annealed oligos 1:100, e.g., add 2 ul annealed oligos to 198 ul water
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
	5. Add 6 ul per ligation mix to 50 ul Competent cell, super Stbl3, for transformation.
	6. After transformation, add 250 ul LB Broth into tube and incubate at 37 degree for 30 min.
	7. Plate 80 ul cells on LB Agar plates, containing 100 ug/ml ampicillin and grow in an incubator overnight at 37 degree.
	8. Pick up the suvived colonies and grow on larger scale for isolation.
	9. Sequence check.

