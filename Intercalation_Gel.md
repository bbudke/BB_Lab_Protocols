# Quantification Of DNA Intercalation By Compounds
By Brian Budke
___
## Preparation And Running Of Gel With Compound
### Overview
This assay measures the extent to which compounds intercalate dsDNA by running negatively supercoiled or relaxed covalently closed circular plasmid DNA through an agarose gel containing the compound to be tested. The compound is also present at the same concentration in the running buffer. Intercalation is detected as faster migration of the relaxed covalently closed plasmid through the gel as positive supercoils are introduced by compound intercalation. The migration of the relaxed plasmid is very sensitive to intercalation, as the introduction of a single positive supercoil can produce a detectable change in migration speed. Thus, very weak intercalators can be studied using this technique. Intercalation can also be detected as slower migration of the negatively supercoiled plasmid, which is relaxed by compound intercalation, though this effect is only visually obvious with stronger intercalators. Each concentration of each compound to be tested requires setting up a separate gel and rig, making the assay very low-throughput. However the assay is very sensitive and has fewer moving parts than intercalation assays that rely on enzymes to nick and reseal circular DNA in the presence of an intercalator, with the assumption that the intercalating compound does not directly interfere with the activities of the enzymes themselves.

The protocol below is optimized for compounds formulated in 100% DMSO. The final concentration of DMSO in the gel and running buffer is 4%. The presence of 4% DMSO does not appear to influence the migration of circular DNA relative to the linear dsDNA ladder. Include a DMSO-only control gel for each experiment.

In order to facilitate precise measurement of the apparent sizes of DNA topoisomers, each plasmid lane is run adjacent to a lane loaded with linear dsDNA ladder.

### Equipment And Reagents
- One agarose minigel rig for each concentration of each compound to be tested.
- Glassware should be rinsed in distilled water if it was autoclaved. The autoclave deposits a residue on everything that goes into it, which can interfere with sensitive assays.
- 50X TAE buffer:
	- 2M Tris base
	- Glacial acetic acid to pH 8.3 - 8.4
	- 50 mM EDTA
- Negatively supercoiled and relaxed closed circular plasmid DNA
	- Negatively supercoiled plasmid DNA is CsCl-purified from _E. coli_. Refer to the protocol for [CsCl Purification Of Supercoiled Plasmid DNA](CsCl_Plasmid_Prep.md).
	- Relaxed closed circular plasmid DNA is prepared from CsCl-purified negatively supercoiled plasmid DNA by following the protocol for [Preparation Of Relaxed Closed Circular dsDNA](Topo_Relaxed_DNA.md).
	- I routinely use pRS306, which is 4,373 bp long. Small plasmids work best for this assay because the topoisomers with the lowest absolute linking number are better resolved from the relaxed DNA.
- Gel loading dry with xylene cyanol FF.

### Procedure
1. Prepare 1X TAE sufficient for all gels and gel rigs, plus dead volume.
	- Each minigel uses 35.4 ml total volume.
	- The running buffer in each gel rig uses 290 ml total volume.
	- Adjust the amount of water used to make up the 1X TAE to account for the final concentration of 4% DMSO in all solutions. The DMSO ± compound will contribute 1/25<sup>th</sup> of the final volume.
1. Prepare a sufficient volume of a 25X dilution of each compound in 100% DMSO for both the gel and the running buffer.
1. Prepare a molten agarose stock sufficient for all gels, plus dead volume.
	- Remember to replace any evaporated water by bringing the volume of the molten agarose back up to the original volume with ultrapure water.
1. Distribute molten agarose and 1X TAE running buffer into clean flasks for each gel to be run. Once the molten agarose has cooled to 55 - 60 °C, add DMSO ± compound to each respective flask, mix, and pour into casting trays.
1. Add DMSO ± compound to each respective flask of running buffer and mix.
1. Load gels with 5.0 - 7.5 μl ladder and 150 ng per lane of plasmid. I typically load the following lanes:
	- Ladder
	- Supercoiled pRS306
	- Topoisomerase I-relaxed pRS306, prep 1
	- Ladder
	- Supercoiled pRS306
	- Topoisomerase I-relaxed pRS306, prep2
	- Ladder
1. Run the gels at 5 V/cm until the xylene cyanol has migrated 2/3 the length of the gel, about 2 1/2 hours.
	- The gels will give off a smell of old cabbage as they are running, which is due to oxidation of the DMSO.
1. Stain the gels for 30 minutes in 0.5 μg/ml ethidium bromide in water, rinse in distilled water, and de-stain for 30 minutes in distilled water.
1. Photograph gels under UV transillumination.

## Analysis Of Agarose Gel Images
### Overview
Intercalation is quantified by measuring the median distance of topoisomer migration relative to the position of the relaxed band and the expected position for the fully-supercoiled band. The lanes containing supercoiled plasmid DNA in the DMSO-only control gel provide the expected position of the fully-supercoiled band, while the position of the relaxed band is obtained from the same lane containing topoisomers to be measured, since intercalation does not affect the migration of this band relative to the linear dsDNA markers.

### Example Workflow
1. Make a two-dimensional plot of DNA staining intensity vs distance migrated in pixels or centimeters for each lane of each gel.
1. For the plot of each lane, convert the distance migrated in pixels or centimeters to the apparent base pair distance migrated, using the adjacent ladder for each lane.
1. For the plot of each lane containing relaxed DNA, mark the positions of the relaxed band and the expected position of the fully-supercoiled band, which is the position of the supercoiled DNA band in the DMSO-only control.
1. For the plot of each lane containing relaxed DNA, calculate the median distribution of topoisomers.
	- Take the area under the curve containing all the topoisomers. The median is the point along the x-axis that divides this area in half.
	- Be sure to include the topoisomer band with the lowest absolute linking number, which may appear as a shoulder on the relaxed DNA band.
1. An 'intercalation score' can be calculated as any additional distance that the median distribution of topoisomers shifts in compound-containing gels compared to the DMSO-only control gel.