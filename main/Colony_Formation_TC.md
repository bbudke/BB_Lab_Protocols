# Clonogenic Survival Assay For Adherent Tissue Cells
By Brian Budke
___
## Treatment And Seeding Of Cells
### Overview
The following setup is used to test the toxicity of an agent when present alone or to detect synergistic lethality between two agents. For single-agent toxicity, the agent is usually titrated in a series of doses that are evenly-spaced along a logarithmic axis. For synergy, a two-dimensional square matrix of dose pairs is set up; a square matrix is preferred to permit easy synergy analysis in [R](https://cran.r-project.org/) using the [SynergyFinder](https://bioconductor.org/packages/release/bioc/html/synergyfinder.html) package. When two agents are being tested, the first agent is typically some kind of established cancer therapy (e.g. X-rays, cisplatin, topotecan) and the second agent is an experimental compound (e.g. [RI(dl)-2](https://www.ncbi.nlm.nih.gov/pubmed/27049177)).

This assay is almost always used in our group to study compounds that are dissolved in DMSO. Therefore, DMSO is present at 0.5% final concentration in each sample. Also, because measuring synergy between two DMSO-formulated drugs is the most common application of this assay, each sample is set up by combining 1 ml media + DMSO ± agent 1, 1 ml media + DMSO ± agent 2, and 1 ml media + cells for 3 ml total. It doesn't matter if agent 1 happens to be radiation or if a compound is formulated in something other than DMSO; the samples are always set up in the above manner to ensure consistency.

### Materials And Reagents
- 6-well tissue culture plates
- Sterile polypropylene tubes
	- Do not used autoclaved plastics. The autoclave deposits a residue onto autoclaved objects that may affect the results of sensitive tissue culture-based assays.

### Initial Cell Culture
- For experiments in which one or two agents are combined in liquid form with cells at the time of plating, a single dish of subconfluent cells may be used.
- For experiments in which cells are treated with one agent prior to plating (e.g. when radiation is administered), the cells are grown to subconfluence in one dish per dose of the agent being tested. For example, in an experiment in which six doses of X-rays including 0 Gy are being tested, there are six culture dishes that each get their own dose of radiation. If X-rays are to be administered, warm up the Maxitron before starting the procedure below.

### Procedure
1. For each agent, make working stocks of medium + DMSO ± compound by diluting compounds in 100% DMSO to 400X their final concentration and then add complete medium to dilute the compounds to 3X their final concentration and the DMSO to 0.75%.
	- If compounds are made up in a vehicle other than DMSO, make the 400X dilutions in that vehicle first and then add medium + 0.75% DMSO, also keeping the vehicle concentration the same across all the samples.
1. Add 1 ml of medium + 0.75% DMSO ± agent 1 to the respective sample wells and then add 1 ml of medium + 0.75% DMSO ± agent 2 to the respective sample wells. Move the plates to the CO<sub>2</sub> incubator to allow the temperature and pH to re-equilibrate.
	- Both of these additions are performed even if one or both agents are not in liquid form (e.g. radiation) or absent. For consistency across experiments, these two additions are always performed.
1. If radiation is being administered:
	- Take the dishes of cells down to the warmed-up Philips RT250 Maxitron, including the control plate that receives 0 Gy. Use a disinfected styrofoam or plastic box to transport the cells.
	- Check that the 10 cm<sup>2</sup> cone and 1 mm Cu filter are installed. Set the distance from the end of the cone to the table to 10 cm.
	- Irradiate the respective plates for the time indicated in the table on the wall near the control panel. The dose rate is about 1.54 Gy/min with the above configuration.
1. Collect the cells from the dish(es) by trypsinization, spin down, and resuspend in 3 ml or appropriate volume of complete medium. Count the cells using the hemocytometer, taking care to get accurate counts.
1. Dilute the cells in complete medium to 1000 cells per ml. Add 1 ml of this suspension to each of the wells.
	- Because the dilutions are performed in polypropylene tubes that have a maximum volume of 50 ml, up to 48 wells can be seeded from one suspension, with a 2 ml dead volume. If more wells are to be seeded in the same experiment, consider how the experiment can be factored and make separate suspensions for each group. For example, consider an experiment in which a single chemotherapeutic agent is set up with four different experimental compounds in dose pairs. Each combination of chemotherapeutic agent and test compound is tested in a 6 x 6 matrix of dose pairs, 36 wells per combination and 144 wells for all four combinations. In this experiment, there should be four identical dilutions of cells in medium, one for each of the four combinations.
	- Seeding 1000 cells per well is a good starting point for most cell lines. Adjust the seeding density as needed. There should be a few hundred of well-separated colonies in the control well(s) by the time they grow to >50 cells per colony, assuming a cell line that forms 0.5 - 1.0 mm diameter colonies.
1. Distribute the cells evenly in each well by shaking the plates five times along the north-south axis, pausing for a couple seconds, and the shaking five times along the east-west axis. Repeat 7 times.
	- Rotational shaking will cause all the cells to accumulate in the center of the wells.
1. Incubate the plates until colonies of at least 50 cells form in the control well(s). This is usually 7 - 14 days. For consistency, once the incubation time for a particular cell line is known, use that incubation time for all subsequent experiments.

## Staining And Automatic Scoring Of Colonies
### Materials And Reagents
- Staining solution:
	- 6% (w/v) glutaraldehyde
	- 0.5% crystal violet
	- To make the solution, dissolve the crystal violet in 6% (w/v) glutaraldehyde in water by stirring for a few hours at room temperature. Filter the solution to remove any undissolved clumps of the dye.
	- The solution can be reused several times. Filter the solution before use; the same filter apparatus can also be rinsed in water and reused a few times. If the stock solution is getting low, it can be topped up by adding in some newly-made solution.
- Large autoclave basin
- Light table and camera

### Procedure
1. Aspirate the media from each well into a waste flask.
1. Wash each well with 1 - 3 ml PBS.
1. Aspirate the wash from each well into a waste flask.
1. Add enough staining solution to cover the bottom of each well.
1. Incubate for at least 30 minutes, up to a few hours.
1. Transfer the staining solution from each well back into the stock bottle.
1. Fill up a large autoclave basin with cold tap water. Submerge each plate and let stand for 5 minutes.
	- During the wash, I like to have the plates oriented vertically, using the surface tension on one edge of the plate to hold it upright in the water. This way, the excess stain falls away from the bottom surface of the well.
1. Remove the plates from the basin, empty the basin and refill with cold tap water, and repeat the above wash step.
1. Remove the plates from the basin, shake away excess water, and air-dry.
	- I dry each plate by standing it up on the long side of the plate, waiting 5 - 10 minutes, shaking off more excess water that collects at the bottom of the plate, and standing it up again on the long side and air-drying a few hours or overnight. This way, most of the excess water is removed and any water that accumulates does so at the peripheral edge of the wells where it won't interfere with counting.
	- If water is allowed to pool and dry in middle of the wells, it can leach dye from colonies and form a coffee stain ring where it dries; this may interfere with automatic colony detection.
1. Acquire an image for each individual well:
	- Warm up the light table. Some light tables need to be left on for up to 5 minutes to reach a steady light output.
	- Position the light table below the camera and set up to take pictures. We use a Bio-Rad Gel Doc system to take pictures, though the settings below can be applied to any camera system.
		- No filter (move the UV filter out of the way)
		- Maximum tele zoom and nearest focus setting
		- White mode
		- Exposure time of 0.05 seconds.
		- Iris adjusted so that the brightest pixels are about 80% saturated with the light table positioned below the camera.
		- Save each image and export a TIFF copy.
		- As a courtesy to your fellow lab-mates, who use the Gel Doc almost exclusively for photographing agarose gels stained with ethidium bromide, move the UV filter back into position and open the iris all the way when you are done taking pictures.
1. Use the [BB Macros](https://github.com/bbudke/BB_macros) set for [NIH ImageJ](https://imagej.nih.gov/ij/) to automatically score colonies.
	- The first time colonies from a particular cell line are scored, examine one of the wells at 40X magnification to get an idea of how big and brightly-stained a 50-cell colony looks. Adjust the focus enumeration settings in the macro so that it looks like colonies with at least 50 cells are being counted.
	- For consistency, use the same macro settings to score colonies for each cell line between experiments.
