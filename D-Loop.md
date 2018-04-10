# D-loop Assay
Adapted from protocol by Yuen-Ling Chan (University of Chicago)
___
## Overview
The D-loop assay detects homologous strand invasion catalyzed by recombinase proteins such as RecA and RAD51. A labeled oligonucleotide (e.g. a 90-mer with a 5' Cy5 or <sup>32</sup>P label) is first incubated with recombinase protein to allow formation of nucleoprotein filaments and then a negatively-supercoiled dsDNA plasmid with homology to the oligonucleotide is added. Strand invasion is detected as a slower-migrating band on an agarose gel corresponding to the labeled oligonucleotide complexed with the plasmid.

## Gel Preparation
- Make gels and buffers the day of use.
- If using autoclaved glassware, rinse it with deionized water to remove any residue from the autoclave.
- Prepare a single stock of 1X TAE buffer sufficient for all gels and electrophoresis tanks.
	- The TAE buffer used in this assay is different from the Sambrook et al recipe: the final pH of the 1X solution is 7.5 and the conductivity is around 2 μS/μs.
	- If using the medium-size gel rigs, make 90 ml for one gel (up to 20 lanes), 190 ml for two gels (up to 40 lanes), and 690 ml for each electrophoresis tank, plus some dead volume.
- Prepare 0.9% agarose 1X TAE gels: boil in microwave for 2:30 min (1 gel) or 3:30 min (2 gels), add Milli-Q water to replace any evaporated volume, cool to 45 - 55 °C, and pour 90 ml into each casting tray. Cover loosely to protect from dust.

## Reaction Setup
### Overview
- Reactions are set up in individual 0.5 ml tubes. Add each reaction component as a single drop on the inner wall of the tube and mix by quick-spinning and gently flicking the tube. The same pipette tip can be used for all tubes in this way to save plastic, if you add reagents drop-wise and don't touch the pipette tip to the tube.
	- The deproteinization solution containing SDS is added directly to the reaction at the bottom of the tube using a new pipette tip for each tube, since handling it in the manner above is not accurate enough.
- Up to 40 reactions are set up in one experiment.
- Incubations are in a 37 °C water bath.
- The procedure below is for testing the effects of compounds on D-loop formation. For assays in which drugs are not being tested, simply omit the steps involving handling of compounds and make up reactions without DMSO.
- Concentrations of recombinase, ssDNA, and dsDNA are optimized for detecting D-loops catalyzed by HsRAD51 using the Cy5-labeled ssDNA probe.

### Materials And Reagents
- Plastics: Avoid using anything that has been autoclaved. The residue from the autoclave can inhibit many biochemical reactions. Use regular DNAse-free RNAse-free low-adhesion polypropylene tubes and tips.
- Recombinase proteins: These should be stored in single-use aliquots at -80 °C that have undergone no more than three total freeze-thaw cycles.
- The standard ssDNA used in this assay is the 5'-Cy5 labeled 90-mer, 306.90, with the 5' → 3' sequence: tacgaatgcacacggtgtggtgggcccaggtattgttagcggtttgaagcaggcggcagaagaagtaacaaaggaacctagaggcctttt
- The standard supercoiled dsDNA plasmid target is [pRS306](https://www.addgene.org/vector-database/3971/), CsCl-purified from _E. coli_. There should be no more than 5% nicked plasmid in the preparation.
- Store ATP, TCEP/DTT, BSA, and ssDNA at -20 °C in aliquots. The dsDNA is kept in storage aliquots at -20 °C, with a single working aliquot being kept at 4 °C to limit freeze-thaw cycles.
- For any drugs or compounds to be tested, these are stored at -20 °C in 100% DMSO (or other solvent if DMSO is not suitable) at 50 mM or less if not soluble at this concentration. In all assays where compounds are being tested, DMSO is included in all samples at a final concentration of 5% at the time of nucleoprotein filament formation, even for compounds that are formulated in water and not DMSO (e.g. chloroquine).

### Procedure
1. Prepare dilutions of compounds in their storage solvent (usually 100% DMSO) to 20X their final concentration at the time of nucleoprotein filament formation.
1. Prepare a 5X D-loop reaction buffer master mix:

Item | Conc. units | Stock conc. | Master mix conc. | Final conc.
:--- | ---: | ---: | ---: | ---:
HEPES-NaOH pH 7.2 | mM | 1000 | 125 | 25
ATP | mM | 100 | 5 | 1
MgCl<sub>2</sub> | mM | 100 | 5 | 1
TCEP or DTT | mM | 100 | 5 | 1
BSA | μg/ml | 6600 | 500 | 100

1. Prepare a 10X dilution of recombinase protein in appropriate protein dilution buffer.
	- For HsRAD51, this is a 15 μM dilution made in 10 mM Tris-HCl pH 8.0, 150 mM NaCl, 10% glycerol, for a final HsRAD51 concentration of 1.5 μM at the time of dsDNA addition.
1. Prepare a 10X dilution of labeled ssDNA in 10 mM Tris-HCl pH 7.5 for a final concentration of 20 nM at the time of D-loop formation.
	- It is not necessary to heat-denature the ssDNA if a 90-mer oligonucleotide is used.
1. Prepare a 10X dilution of supercoiled plasmid dsDNA in 10 mM Tris-HCl pH 7.5 for a final concentration of 5 nM at the time of D-loop formation.
1. Prepare master mixes of reaction buffer, water, and protein buffer ± recombinase. Each reaction at the time of D-loop formation will have the composition listed in the table below:

Item | Amount per reaction | Part of master mix
:--- | ---: | :---:
5X D-loop reaction buffer | 2 μl | Y
10X recombinase or buffer | 1 μl | Y
Ultrapure water | 3 μl<sup>†</sup> | Y
22.5% DMSO ± compound | 2 μl |
10X labeled ssDNA | 1 μl |
10X supercoiled dsDNA | 1 μl |
Total volume | 10 μl |

	† 5 μl if not testing compounds.

1. To the compound dilutions in 100% DMSO above, add 3.44 volumes of water so that the compounds are now at 4.5X their final concentration at the time of nucleoprotein filament formation. This will also bring the DMSO concentration in the dilutions to 22.5%, which is 4.5X the final concentration of 5% at the time of nucleoprotein filament formation. If the compounds were made in water instead of DMSO, then dilute them to 4.5X using water + 22.5% DMSO so that all reactions contain the same amount of DMSO regardless of what compound is being tested.
1. Pre-incubate compounds with RAD51 in reaction buffer: combine 6 μl of master mix with 2 μl 4.5X compound in 22.5% DMSO and incubate for 5 minutes at 37 °C.
1. Form nucleoprotein filaments: add 1 μl of 10X ssDNA to each tube and incubate for 5 minutes at 37 °C.
1. Form D-loops: add 1 μl of 10X dsDNA to each tube and incubate for 20 minutes at 37 °C.
1. Deproteinize: add 2 μl of deproteinization solution to each tube and incubate for 5 minutes at 37 °C.
	- Deproteinization solution is 5% SDS + 5 mg/ml proteinase K.
1. Add 3 μl gel loading solution.
	- Gel loading solution is simply 32% glycerol. Xylene cyanol and bromophenol blue may also be added, but it is necessary to leave out the loading dyes if a fluorescently-labeled oligo is being used, as the dyes are fluorescent too and will interfere with detection.

## Gel Run And Imaging
- For each reaction, load the entire amount into the gel.
- Run the gels at 60 V (3 V/cm), up to 120 mA per gel to avoid overheating. Run the gels for 2.5 hours at room temperature. It is not necessary to cover up the gels if a fluorescent oligo is being used, though the gels should not be in direct sunlight. If the electric current is too high, lower the voltage and increase the running time accordingly so that the gels are run the right distance without overheating.
- Gel imaging:
	- For fluorescent oligo detection, rinse the gel thoroughly with distilled water, transfer the wet gels to an appropriate imager (e.g. a Typhoon scanner equipped with Cy5 filters), set the focal plane to + 3 mm, select 100 px/cm resolution, set the mode to fluorescence, select the appropriate filter, select to normal sensitivity, and set the PMT voltage to 600 (the default).
	- For detection of <sup>32</sup>P, refer to the [Gel Drying And Imaging For Radioactive Gels protocol](Gel_Drying_And_Imaging.md).