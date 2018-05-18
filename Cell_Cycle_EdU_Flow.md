# Determination Of Cell Cycle And EdU Incorporation By Flow Cytometry
By Brian Budke
Adapted from ThermoFisher Click-it EdU kit instructions and Sun _et al_ 2012 (Cytometry A 81A:901-909).
___
## Treatment And Labeling Of Cells
### Overview
- This assay is used to measure cell cycle progression and the DNA synthesis rate in a population of tissue cells. Cell cycle progression is determined by propidium iodide (PI) staining of total DNA content in fixed and permeabilized cells. New DNA synthesis is measured by detection of incorporated 5'-ethynyl-2'-deoxyuridine (EdU), an analog of deoxythymidine. The protocol below is optimized for determining what effect compounds have on these endpoints.
- Because it is necessary to set up a compensation matrix for flow analysis, EdU-negative and PI-negative controls must be set up as well. Many test compounds also impart some fluorescence to cells, so it is also recommended to have these controls for each concentration of each compound.

### Initial Cell Culture
- Use one or more 6-well plates of tissue cells. Cells should have been seeded at least 20 hours before treatment at a sufficient density to provide 70% confluence in the control wells by the time cells are collected for flow cytometry. This should also be enough to provide 0.5 - 1.0 x 10<sup>6</sup> cells per sample.
- Cells should be growing in 2.0 ml of complete medium per well. During labeling and treatment, two 0.5 ml additions of complete medium ± compound or ± EdU are made, bringing the total volume to 3.0 ml per well.

### Reagents
- 10 μM EdU
	- Dissolve in 100% DMSO and store in aliquots at -20 °C.

### Procedure
1. For each compound, make a 400X dilution of compound in 100% DMSO and then add complete medium to dilute the compounds to 6X their final concentration and the DMSO to 1.5%.
	- If compounds are made up in a vehicle other than DMSO, make the 400X dilutions in that vehicle first and then add medium + 1.5% DMSO, also keeping the vehicle concentration the same across all the samples.
1. Make a 4000 μM (400X) dilution of EdU in 100% DMSO and then add complete medium to dilute the EdU to 60 μM (6X) and the DMSO to 1.5%. Also make complete medium + 1.5% DMSO without EdU for the EdU-negative controls.
1. Retrieve the plates of growing cells from the incubator and add 0.5 ml per well of the medium + 1.5% DMSO ± compound.
1. Add 0.5 ml per well of the medium + 1.5% DMSO ± EdU and return the plates to the incubator for the desired amount of time.

## Click Reaction To Detect EdU Incorporation
### Overview
- Cells are harvested, washed, fixed, and permeabilized so that total DNA can be stained with PI and incorporated EdU can be tagged with a dye-azide. RNAse is added so that only DNA is stained by PI. EdU is tagged via a cycloaddition reaction between the alkyne group of EdU and the azide group of the dye. The cycloaddition reaction is catalyzed by Cu(I), which is provided by Cu(II) in a mildly-reducing environment. Sodium ascorbate is used as a reducing agent and must be prepared fresh within minutes of use. Sulfo-cyanine 5 azide is used below, though any dye azide can be used.
- Any DNA stain such as DAPI or PI can be used, as long as there isn't too much bleed-through with the dye used to detect EdU.
- It is convenient to transfer samples to 1.5 ml tubes following trypsinization and centrifugation; these tubes can be stacked into 50 ml conical vials and spun in a clinical centrifuge. When removing supernatants, decant and leave a small amount to keep the pellet from going dry. To prevent clumping, cells should be spun down at the lowest speed that will give a pellet. This is typically 300g - 500g. Resuspension should also be done as gently as possible; simply pipetting a stream of buffer directly onto the pellet should be enough to completely resuspend it, assuming the cells were not spun down too hard.
- Time consideration: there are 60 minutes total incubation time and almost half an hour of centrifugation time. This doesn't include handling time. When processing 40 samples following the procedure below, it took me 4 hours from the start of trypsinization to having all the samples in flow tubes.

### Materials And Reagents
- Wash buffer
	- 1X PBS
	- 1 mM EDTA
	- 1% BSA
- Fixative solution
	- 4% (w/v) paraformaldehyde dissolved in 1X PBS by stirring at 60 - 70 °C. Cool to room temperature, filter, and store at 4 °C for up to two weeks.
- Permeabilization buffer
	- 0.5% Triton X-100 in 1X PBS, made fresh the day of use.
- Click reaction buffer
	- 1X TBS (PBS will cause CuSO<sub>4</sub> to crash out)
	- 2 mM CuSO<sub>4</sub>
	- 1 μM sulfo-cyanine 5 azide (added from a 1 - 10 mM stock made in 100% DMSO)
	- 20 mM sodium ascorbate (added from a 1 M stock made in water within the last 15 minutes)
	- 10% DMSO
	- Make fresh within minutes of use. Protect from light.
- FACS resuspension buffer
	- 1X PBS
	- 1 mM EDTA
	- 1% BSA
	- 0.5% Triton X-100
	- 50 μg/ml DNAse-free RNAse A
		- Required if PI is used; optional for DAPI
	- 50 μg/ml PI (also make a smaller aliquot of buffer without PI for the PI-negative controls)
- Polypropylene 1 ml micro titer tubes (Genesee 14-144) nested into polystyrene 5 ml flow cytometry tubes (Falcon 352008)
- Styrofoam box with blue ice packs. The box should be large enough to hold a rack of flow cytometry tubes.

### Procedure
1. Harvest cells by trypsinization. Save and spin down the media supernatant and wash along with the trypsinized cells if the cells are loosely-adherent or if there are many floaters.
1. Resuspend the cells to ~10<sup>6</sup> cells per ml in wash buffer; 0.5 - 1 ml per sample is usually fine for this step and all the wash steps below.
1. Spin down the cells, remove the supernatant, and resuspend each sample in 100 μl of fixative solution. Incubate at room temperature for 15 minutes.
1. Spin down the cells, remove the supernatant, and resuspend each sample to ~10<sup>6</sup> cells per ml in wash buffer.
1. Spin down the cells, remove the supernatant, and resuspend each sample in 100 μl of permeabilization buffer. Incubate at room temperature for 15 minutes.
1. Spin down the cells, remove the supernatant, and resuspend each sample to ~10<sup>6</sup> cells per ml in wash buffer. The wash buffer in this step should be EDTA-free, as residual EDTA will chelate out the copper ion in the subsequent click reaction.
1. Spin down the cells, remove the supernatant, and resuspend each sample in 500 μl of click reaction buffer. Incubate at room temperature for 30 minutes.
1. Spin down the cells, remove the supernatant, and resuspend each sample to ~10<sup>6</sup> cells per ml in wash buffer.
1. Spin down the cells, remove the supernatant, and resuspend each sample to ~10<sup>7</sup> cells per ml in FACS resuspension buffer. Keep on ice and protect from light.
	- Remember to resuspend at least one EdU-positive control sample in FACS resuspension buffer without PI to serve as the EdU-positive compensation control.
1. Transfer each sample to a 1 ml micro titer tube that has been placed into a 5 ml flow tube. Keep samples at 4 °C and protected from light.

## Flow Cytometry
- Run at a low flow setting. High flow rates will give high coefficients of variation and the G1/S/G2 phases won't resolve nicely.