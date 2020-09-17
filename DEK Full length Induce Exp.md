Lab Protocol>>>>Project: DEK Work
---
Author: Jiahao Cui>>>>Date: 20200916
---
DEK full length Induce Exp.>>>>Cell System: BL21
---
> After Maxwell's work, BL21 were chosen for further analysis, and two hours of IPTG was adapted from this result.

# Small scale Culture
	1. Add 20 ul Glycerol stock (From NengWei, Maxwell's is missing) into 5 ml LB Broth with 5 ul Ampicillin (100mg/ml)
	2. Incubate with shaking at 37 degree and 200 rpm for overnight culture.

# Recovery incubation
	1. Following overnight culture, add 1 ml culturing mix into 9 ml LB/AMP Broth, to make a 10 time dilution.
	2. Further culture until OD600 reach a range of 0.5~0.6

# Set different Incubating and Inducing Group
	1. Add 1 ml culturing mixture into a new 1.5 ml tube, make this 15 tubes.
	2. Group setting:
	>>>>Room Temperature
			1. 0.8 mM IPTG
			2. 1.6 mM IPTG
			3. 3.2 mM IPTG
			4. 6.4 mM IPTG
	>>>>37 degree
			1. 0.8 mM IPTG
			2. 1.6 mM IPTG
			3. 3.2 mM IPTG
			4. 6.4 mM IPTG
	3. Incubate tubes for 2 hours

# SDS-PAGE
```
1. centrifuge the tubes at 10,000 xg at 4 degree for 5 min.
2. Discard supernatant
3. Add lyse cells using 40 ul 2% SDS.
4. Heat tubes at 95 degree for 15 min.
5. Mix with Protein loading dye, Beyotime Company.
6. Load samples onto 10% SDS gel. Make four gels, two for Western Blot, two for Coomassie Blue.
	>>>>10 % Separating Gel
		- 30% PA, 4.2 ml
		- 5 % SG, 2.5 ml
		- water, 5.7 ml
		- TEMED, 20 ul
		- 20% APS, 75 ul
	>>>> 4% Stacking Gel
		- 30% PA, 0.665 ml
		- 5 % STG, 2.5 ml
		- water, 1.8 ml
		- TEMED, 20 ul
		- 20% APS, 60 ul
7. Run the separation at 110V for 90 min.
```

# Coomassie Blue Stain
	stain the gel using Coomassie Super Fast Blue from Beyotime for 15 min, and destain using DEPC water.

# Western Blot
	1. Prepare transfer Buffer, chilled to 4 degree to improve heat dissipation.
	2. Wash the PAGE Gel using Transfer for few seconds.
	3.Prepare the PVDF
		- Wet the PVDF in methanol for 15 seconds.
		- Carefully place the PVDF in Milli-Q water and soak for 2 minutes. 
		- Soak the PVDF in Transfer Buffer for 15 min.
	4.Make filter paper gel sandwich model. (Cathode to the gel, Anode to the PVDF)
	5. Set the current:
		- 0.8 mA/cm2 >>>> 2 hours
		- 1.2 mA/cm2 >>>> 1 hour
		- 2.5 mA/cm2 >>>> 45 minutes
		- 4.0 mA/cm2 >>>> 30 minutes

# Antibody staining
	1. Block the PVDF for 1 hour at RT using 5% skim milk.
	2. Incubate PVDF with Primary Antibody (GST anti-mouse, AG768, Beyotime) for 2 hours at RT or overnight at 4 degree.
	3. Wash the PVDF in three washes of PBST, 5 min each.
	4. Incubate the PVDF with Secondary Antibody (HRP Goat anti mouse, A0216, Beyotime) at RT for 1 hour.
	5. Wash the PVDF in three washes of PBST, 5 minutes each, then rinse in PBS.
	6. Remove the excess reagent ad cover PVDF in plastic wrap.
	7. Acquire image using ECL, in a Dark Room
		- Mix ECL buffer components 1:1, and place on blot for 2 min.
		- Drain excess reagent
		- Cover damp blot with plastic wrap, gently smooth out any air pockets.
		- Transfer PVDF to the machine avoiding the lights.
		- Get image.
