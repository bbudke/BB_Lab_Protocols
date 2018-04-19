# Determination Of Cell Cycle And EdU Incorporation By Flow Cytometry
By Brian Budke
___
## Treatment And Labeling Of Cells
### Overview
- This assay is used to measure cell cycle progression and the DNA synthesis rate in a population of tissue cells. Cell cycle progression is determined by propidium iodide (PI) staining of fixed and permeabilized cells while DNA synthesis is measured by detection of incorporated 5'-ethynyl-2'-deoxyuridine (EdU), an analog of deoxythymidine. The protocol below is optimized for determining what effect compounds have on these endpoints.
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

### Reagents
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
	- 0.1 μM sulfo-cyanine 5 azide (added from a 1 - 10 mM stock made in 100% DMSO)
	- 20 mM sodium ascorbate (added from a 1 M stock made in water within the last 15 minutes)
	- 10% DMSO
	- Make fresh within minutes of use. Protect from light.
- FACS resuspension buffer
	- 1X PBS
	- 1% BSA
	- 0.5% Triton X-100
	- 50 μg/ml DNAse-free RNAse A
	- 50 μg/ml PI (also make a smaller aliquot of buffer without PI for the PI-negative controls)