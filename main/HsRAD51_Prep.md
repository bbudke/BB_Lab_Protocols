# HsRAD51 Protein Prep
By Brian Budke, modified from protocol by Tyler Bold

___
## Popcorn
### Overview
This first part of the protein prep deals with transforming _E. coli_ B with a plasmid that expresses human RAD51 protein under IPTG, growing a large-scale culture expressing the protein, and freezing the bacteria into popcorn with liquid nitrogen. During expression, the tag on the expressed protein is biotinylated, allowing it to be captured on streptavidin beads and eluted with TEV protease, which cleaves off the biotinylated tag.

### Materials And Reagents
- pMCSG16-HsRAD51 (transforms to ampicillin resistance) at 10 ng/μl
- _E. coli_ BL21 DE3 pBirA (chloramphenicol-resistant) electrocompetent cells
- SOC medium
- LB agar plate with 100 μg/ml ampicillin and 34 μg/ml chloramphenicol
- One 2 L Erlenmeyer flask with 0.5 L LB medium with 100 μg/ml ampicillin and 34 μg/ml chloramphenicol
- Three 3 L baffled Fernbach flasks each with 1 L LB medium with 100 μg/ml ampicillin and 34 μg/ml chloramphenicol
- 1 M IPTG
- 1 mg/ml D-biotin in 100% DMF
- Tris buffer (20 mM Tris-HCl pH 8.0, 300 mM NaCl, 1 mM DTT), chilled

### Equipment
- Electroporator
- 1 mm electroporation cuvette
- Shaker incubator with room for the three Fernbach flasks
- A 1 L dewar flask for holding liquid nitrogen and a smaller dewar flask for freezing down popcorn
- Three 1 L centrifuge buckets and a floor centrifuge that can spin these down

### Procedure (Day 1)
1. Electroporate 50 μl of electrocompetent cells with 2 μl (20 ng) of pMCGS16-HsRAD51 using the presets for _E coli_, 1.8 KV, 1 mm. The time constant should be around 5 ms. Just before pulsing, get 1,000 μl of SOC medium ready by drawing it into the pipette, holding this in one hand and operating the electroporator with the other. Hit the pulse switch, wait for it to administer the pulse, and immediately add the 1,000 μl of SOC medium to the cuvette.
1. Transfer the electroporated cells in SOC to a 1.5 ml tube and rotate at 37 °C for 30 minutes to 1 hour.
1. Spin down the cells at 12,000 g for 1 minute, decant off the supernatant, and resuspend the cells in the residual 30 - 60 μl of supernatant. Spread the suspension onto the LB agar plate with 100 μg/ml ampicillin and 34 μg/ml chloramphenicol using a glass rod, spreading evenly in one quadrant of the plate and streaking for single colonies on the remainder of the plate.
1. Incubate overnight at 37 °C.

### Procedure (Day 2)
1. Pick several well-isolated colonies and inoculate into the 2 L Erlenmeyer flask with 0.5 L LB medium with 100 μg/ml ampicillin and 34 μg/ml chloramphenicol.
1. Incubate on the bench at room temperature overnight.

### Procedure (Day 3)
1. Inoculate 80 ml of the above starter culture into each of the three 3 L baffled Fernbach flasks each with 1 L LB medium with 100 μg/ml ampicillin and 34 μg/ml chloramphenicol. Grow at 37 °C, shaking at 235 rpm, until the culture reaches an OD<sub>600</sub> of 0.4 to 0.5. It will take about 4 - 5 hours to reach this point.
1. Once the culture reaches OD<sub>600</sub> 0.4 to 0.5, lower the temperature to 30 °C and continue shaking. Thaw out the IPTG and keep it on ice along with the D-biotin in DMF.
1. When the culture is between OD<sub>600</sub> 0.7 to 1.0, add 500 μl of IPTG (to 0.5 mM) and two 611 μl additions of D-biotin in DMF (to 5 μM) to each culture and continue shaking at 235 rpm overnight at 30 °C.

### Procedure (Day 4)
1. Spin down the culture in each flask in a 1 L centrifuge bucket at 6,000 g at 4 °C for 20 minutes.
1. Pour off the supernatant, add 100 ml of chilled Tris buffer to each bucket, and resuspend the pellet by vortexing. Spin down at 6,000 g at 4 °C for 10 minutes, pour off the wash, and repeat this step for a total of two washes. During the last spin, fetch 0.5 L of liquid nitrogen in the larger of the two dewar flasks and bring it back to the lab.
1. Resuspend each washed pellet in 10 ml of chilled Tris buffer. Pour some of the liquid nitrogen into the smaller dewar flasks, to about 1 inch from the top. Add the cell suspension from one of the buckets drop-wise to the smaller dewar, wait for it to finish bubbling, decant the liquid nitrogen back into the larger dewar, and transfer the popcorn to a 50 ml conical vial (a funnel helps). Repeat for each of the buckets with cell suspension. Store popcorn at -80 °C for up to a week.

## Protein Purification
### Overview
HsRAD51 protein is tagged at one end with an AviTag, which becomes biotinylated _in vivo_ during protein expression and has a TEV protease cleavage site that allows the protein to be eluted off streptavidin beads leaving a 2 amino acid remnant of the tag attached to the protein. The RDB-10 storage buffer contains DTT, which may inactivate some RAD51 inhibitors that function by covalent modification of RAD51 by a Michael addition reaction. If the RAD51 prep is going to be used to study these compounds, then 1 mM TCEP should be used instead of DTT in the final wash and in the storage buffer.

Time consideration: This can take up to 10 hours, depending on how fast the final concentration step goes. There are no overnight stopping points.

### Materials And Reagents
- Protease inhibitor tablets (Roche Complete Mini)
- Tris buffer (20 mM Tris-HCl pH 8.0, 300 mM NaCl, 1 mM DTT), chilled
- Streptavidin beads (Pierce Ultralink)
- RDB-10 buffer (10 mM Tris-HCl pH 8.0, 150 mM NaCl, 10% glycerol, 1 mM DTT), chilled

### Equipment
- French press with 1 inch internal diameter pressure cell
- Sorvall SS-34 rotor, SLA-1500 rotor, and floor centrifuge
- Fine glass rod (e.g., a pasteur pipette sealed at the end with a flame)
- Swinging bucket clinical centrifuge
- Pasteur pipette attached to vacuum trap
- TEV protease (≥ 1 mg/ml)

### Procedure (Day 5)
1. Thaw out the popcorn at room temperature on a rotisserie. This takes about 30 minutes. Keep an eye on the tubes towards the end and transfer them to an ice bucket as soon as they are completely thawed. The cell suspensions should not actually come up to room temperature; they should be allowed to get no warmer than 4 °C.
1. Combine the cell suspensions into a single tube and add a protease inhibitor tablet crushed and dissolved in 1 ml of Tris buffer.
1. _This step uses the French press. If you are not completely familiar with its operation, ask an experienced user to train you._ Set up the pressure cell on a metal holder, upside-down, with the piston inserted into the top of the cell (which is facing down). Screw in the outlet and valve, finger-tight but not too tight. Add the cell suspension from the bottom of the cell (which is facing up). Move the piston upwards to eliminate excess air, cap the bottom, and place right-side-up on the French press. Press at 15,000 PSI (910 PSIG on the high setting), collecting lysate drop-wise into a covered side-arm flask on ice. The ideal flow rate also corresponds to the platform moving up at about 1 millimeter per second. When finished, move the platform down, remove the cell, load the lysate back in, and repeat for a total of two passes at 15,000 PSI. Wash and dry all pressure cell components before returning them to storage at 4 °C.
1. Transfer the lysate to a 38 ml centrifuge tube and spin down at 30,000 g at 4 °C in a Sorvall SS-34 rotor for 30 minutes.
1. During the spin, prepare six 15-ml conical tubes each with 10 ml Tris buffer and 0.5 ml streptavidin beads slurry. Spin down and aspirate off the supernatant, leaving a little behind so the beads don't dry out. Keep on ice.
1. Transfer the supernatant with a pipette to a clean glass flask on ice, measuring the volume as you are transferring it. Bring the volume of the cleared supernatant to 72 ml with Tris buffer.
1. Distribute 12 ml of the supernatant into each of the six conical tubes containing washed streptavidin beads, resuspend the beads with a fine glass rod, and rotate at 4 °C for 1 hour.
1. Spin down the beads briefly in a clinical centrifuge at 1,000 g and aspirate the supernatant with a pasteur pipette attached to a vacuum trap.
1. Resuspend each pellet of beads in 10 ml chilled Tris buffer. Spin down as above, aspirate the supernatant, and repeat for a total of three washes.
1. Resuspend each pellet of beads in 750 μl RDB-10 with 30 μg/ml TEV protease, transfer each aliquot of beads to a 2.0 ml tube, and rotate at 15 - 16 °C for 2 hours.
1. Spin down the tubes briefly in a clinical centrifuge at 1,000 g and transfer the supernatants to a single tube. Try to get all of the supernatant by collecting the supernatants close to the beads, pooling this into a separate tube, spinning it down, and adding the supernatant from this tube to the rest of the supernatant. Spin down the pooled supernatant one more time and transfer the supernatant to a clean tube, leaving any residual beads behind. Save a 50 μl aliquot of the supernatant for protein quantification and gel analysis. Transfer the rest of the supernatant to an Amicon Ultra-15 centrifugal filtration device.
1. Spin the filtration device at 5,000 g at 4 °C in a Sorvall SLA-1500 rotor for 30 minutes with either of the two filter panels on the device facing up. After the spin, estimate the volume remaining in the top chamber of the device and pipette the liquid in this chamber up and down with a 1,000 μl pipette a few times to disrupt any concentration gradient that formed during the spin. Repeat this step, spinning for 15 - 30 minutes at a time, until an 8-fold concentration has been acheived. Try not to over-concentrate the sample.
1. Transfer the concentrated prep from the upper chamber of the device to a 1.5 ml tube and spin down in a microfuge at maximum speed at 4 °C for 15 minutes to pellet any precipitate that may have formed during concentration.
1. Distribute the final prep into aliquots of up to 100 μl and store at -80 °C, saving a 20 μl aliquot for protein quantification and gel analysis. The amount of protein recovered from the concentration step should be around 80% and the total amount of protein in the final prep is usually around 1.5 mg. Stored this way, the protein prep is good for a few months for D-loop assays, or longer for less sensitive assays. The protein should not be freeze-thawed more than twice. If less than 100 μl is needed for routine assays, then divide one of the main 100 μl aliquots into single-use sub-aliquots. Hang onto old expired protein preps, as these are still useful for procedures that do not require active protein, such as preparing affinity columns.
