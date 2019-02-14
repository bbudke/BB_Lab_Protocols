# CellTiter Glo Viability Assay
By Brian Budke

Development with CellTiter Glo reagent modified from Promega kit instructions.
___
## Treatment And Seeding Of Cells
### Overview
This assay is used to measure the acute toxicity of compounds in adherent tissue cell lines. Cells are plated into clear-bottom white 96-well tissue culture plates along with 0.5% DMSO ± compound and allowed to grow for an indicated amount of time. No cells are plated in the outermost wells of the plate; these are filled with 200 μl sterile water to serve as a buffer against evaporation, which is noticeable even in a humidified incubator. This leaves 60 wells per plate for assay samples. Each of these assay rows is typically a dilution series of a single compound, with at least one well containing vehicle only.

### Materials And Reagents
- 96-well tissue culture treated polystyrene plates, white with clear flat bottom (e.g. Corning 3610)
- 96-well polypropylene plates
- Multichannel pipette and basins

### Initial Cell Culture
- One or more plates of subconfluent cells may be used for this assay. Be sure to have enough cells to seed assay wells so that the control wells are 50 - 70% confluent by the end of the outgrowth.

### Procedure
1. Prepare 200X dilutions of compounds in 100% DMSO in the 96-well polypropylene plate(s).
	- If the compounds are in a vehicle other than DMSO, then make the dilutions in that vehicle.
1. Add 200 μl sterile water to the outermost wells of each 96-well tissue culture plate.
1. Add 99 μl complete medium to each assay well of each 96-well tissue culture plate.
1. Add 1 μl DMSO ± compound to each respective assay well of the 96-well tissue culture plate(s). Pipette 75 μl up and down three times to mix. Move plates to the incubator to maintain the pH of the medium.
1. Collect cells by trypsinization. Spin down and resuspend in an appropriate volume of complete medium (e.g. 3 - 10 ml). Count cells using the hemocytometer and make dilutions of cells in complete medium.
	- Each well will receive 100 μl of medium + cells and there should be enough cells per 100 μl to seed the wells so that the DMSO-only controls reach 50 - 70% confluence by the end of the outgrowth.
1. Add 100 μl medium + cells to each well and return plates to the incubator.
1. Incubate plates for the desired outgrowth time, typically 1 - 3 days.

## Measurement Of Live Cells Using CellTiter Glo
### Overview
The CellTiter Glo reagent lyses cells and reports the amount of ATP in solution proportional to light produced. Metabolically active live cells will produce ATP but these cells may not necessarily be viable, which distinguishes this endpoint from clonogenic survival.

The procedure below has been modified from the manufacturer's instructions to use less of the expensive CellTiter Glo reagent. This modified protocol is just as sensitive in terms of ATP detection as the manufacturer's protocol, with the ability to quantify ATP concentrations over a linear range from 100 fmol to 1 nmol. Cell lysis also appears to be equally efficient with the modified protocol, as the luminescence signal produced by both methods is the same from 50 cells to 100,000 cells (HEK-293).

### Materials And Reagents
- CellTiter Glo reagent (Promega G7572)
- Multichannel pipette and basins
- 1X PBS
- Plate reader capable of luminescence readings
	- We use a Tecan F200 infinite Pro
- _Optional_: Cells of the same type used in the assay, trypsinized, suspended, and serially-diluted in PBS

### Procedure
1. Remove the medium or water from each well.
1. Add 20 μl PBS to each assay well.
1. _Optional_: Add 20 μl per well of serial dilutions of cells to an empty row of wells in each plate (e.g. the wells that once contained sterile water) so that luminescence readings can be converted to the number of cells.
1. Add 20 μl CellTiter Glo reagent to each assay well.
	- Protect plates from light once the reagent is added.
1. Shake the plates on a rotary platform at ~120 rpm for 10 minutes at room temperature.
1. Add 160 μl PBS to each assay well.
1. Read luminescence.
	- Setting the integration time per well to 200 ms is a good starting point.
	- Read the plates promptly, as the luminescence intensity decays with a half-life of 10s of minutes. This is also why vehicle-only controls are included in each row, as the luminescence signal can noticeably decay even in the time it takes to read a single plate.
	