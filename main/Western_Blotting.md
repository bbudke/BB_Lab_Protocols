# Western Blotting
By Brian Budke
___
## Transfer Of Proteins To PVDF Membrane
### Overview
Proteins are separated on an SDS-PAGE and transferred to a PVDF membrane. The proteins are fixed onto the membrane during transfer, which can then be probed many times with different antibodies. [Preparation of samples](WCE.md) and [running of protein minigels](SDS-PAGE.md) is described elsewhere; this protocol specifically details the transfer and immunoblotting steps. This protocol is optimized for detecting proteins larger than 25 kDa.

### Materials And Reagents
- SDS-PAGE run with protein samples
- PVDF membrane, cut to 9.5 by 6.0 cm
	- Cut a notch in the upper left corner of the membrane for orientation.
	- If more than one membrane is being used in an experiment, cut additional notches to distinguish the membranes.
- Two sheets of Whatman filter paper, cut to the same size as the PVDF membrane plus ~0.5 cm on each side
- Small trays (11 x 8.0 x 1.5 cm)
- Medium trays (17 x 22 x 3.5 cm)
- The rest of the transfer apparatus, including sponges/scrubbing pads, plastic transfer sandwich, and a stir bar
- 10X Towbin buffer
	- 30.3 g/L Tris base
	- 144 g/L glycine
- 1X Towbin buffer
	- 695 ml dH<sub>2</sub>O
	- 100 ml 10X Towbin buffer
	- 5 ml 20% SDS (to 0.1%)
	- 200 ml methanol
	- Make fresh 1 - 2 hours before use, chilling in the cold room so that it is already cold when used

### Procedure
1. Wet the PVDF membrane in a small tray with 100% methanol, then transfer it to another tray with 1X Towbin buffer to hydrate it for at least 5 minutes.
1. Equilibrate the SDS-PAGE, Whatman paper, and sponges with 1X Towbin buffer in small trays for 5 minutes.
1. Assemble the transfer sandwich in a medium tray filled about halfway up with 1X Towbin buffer, ensuring that no bubbles are trapped between layers, starting from the bottom:
	- The black half of the plastic transfer sandwich
	- Sponge/scrubbing pad
	- Whatman paper
	- SDS-PAGE, face-down
	- PVDF membrane, face-down (avoid bubbles!)
	- Whatman paper
	- Sponge/scrubbing pad
	- The clear half of the plastic transfer sandwich, closed over the rest of the sandwich and locked snug but not too tight. Use thinner or thicker sponges/scrubbing pads to get the snug fit just right. Too little tension and the gel will shift during transfer and ruin the blot. Too much tension and the plastic transfer sandwich will eventually break.
1. Set up the transfer rig with stir bar and electrode assembly, filling it about halfway with 1X Towbin buffer. Insert the sandwich into one of the slots in the electrode assembly with the black part of the transfer sandwich facing the black part of the electrode assembly. Top up the transfer rig with 1X Towbin buffer.
1. Connect the transfer rig to the power supply in the cold room, place on a magnetic stirring platform, and transfer overnight at 4 °C, 30V.

## Immunoblotting
### Materials And Reagents
- Blocking buffer
	- Either 5% nonfat dry milk in TBST or 1% BSA in TBST is used as a blocking buffer, depending on the antibody manufacturer's recommendation. The milk version is most commonly used and is used by default unless otherwise specified.
- Primary antibody diluted appropriately in blocking buffer
	- Most primaries are diluted 1:500 to 1:2000.
	- Many primary antibody dilutions can be re-used several times and stored at 4 °C for several weeks with 0.01% thimerosal as a preservative.
- Secondary HRP-conjugated antibody diluted appropriately in blocking buffer
	- I typically use secondary antibodies at a 1:2000 to 1:50,000 dilution.
	- Secondary antibody dilutions are used once and then tossed.
- Small trays (11 x 8.0 x 1.5 cm)
- Deep tray (13 x 10.5 x 8 cm)
- Orbital shaker platform
- TBST
	- 1X Tris-buffered saline
	- 0.05% Tween-20
- Western Lightning Plus-ECL reagent (Perkin-Elmer NEL104001EA)
- CCD imager (we use a FujiFilm LAS-4000)
- 1X Tris-buffered saline
- Heat sealer and bags

### Procedure
1. Move the PVDF membrane from the transfer sandwich directly to a small tray with blocking buffer and incubate for 1 hour at RT on the orbital platform.
	- I have blocked and probed up to four blots in a single tray before. Start with 10 ml for one blot and add 1.5 ml for each additional blot when calculating the amount of blocking buffer and antibody dilution needed.
	- At this point, I cut notches along the side of the membrane with the protein standard ladder to mark the positions of the protein standards, as these will fade with each wash.
1. Transfer the membrane into a small tray with diluted primary antibody and incubate for 2 hours at RT on the orbital shaker.
	- During the antibody incubations, I keep the tray with the blot and the antibody dilution in a large covered petri dish with 1 - 2 mm of water covering the bottom of the petri dish as a makeshift damp chamber to provide humidity. This slows evaporation of the antibody dilution during the incubation.
1. Wash the blot 3 times in a deep tray with ~ 150 ml TBST for 5 minutes at RT.
1. Transfer the membrane into a small tray with diluted secondary antibody and incubate for 1 hour at RT on the orbital shaker.
1. Wash the blot 3 times in a deep tray with ~ 150 ml TBST for 5 minutes at RT.
	- During the washes, boot up the CCD imager so that it has time to cool and is ready to use for the next step.
1. Transfer each membrane to its own small tray. Drain off most of the wash from the membrane without allowing it to dry and add 2 - 3 ml of Western Lightning reagent to each membrane, covering completely. Incubate for 1 minute at RT and then pour off all of the used reagent into a tube and store it at 4 °C.
	- The Western Lightning reagent can be re-used many times and stored at 4 °C for up to a month, at which point it will have lost about 50% of its detection activity.
1. Acquire two images of each blot on the CCD imager: one image under white light illumination and one image at the same zoom/focus under chemiluminescence mode.
1. If the blot is to be re-probed, rinse it briefly in TBST and store it at 4 °C in a heat-sealed bag with 1X tris-buffered saline.

## Stripping And Re-probing
### Materials And Reagents
- Stripping buffer
	- 62.5 mM Tris-HCl, pH 6.8
	- 2% SDS
	- 100 mM β-mercaptoethanol (added right before use)
- Water bath set to 50 °C
- TBST
	- 1X Tris-buffered saline
	- 0.05% Tween-20
- Deep tray (13 x 10.5 x 8 cm)
- Orbital shaker platform

### Procedure
1. Transfer the blot to a heat-sealable bag with 12 - 15 ml stripping buffer. Seal the bag and incubate at 50 °C for 30 minutes, shaking the bag every 10 - 15 minutes.
1. Transfer the blot to a deep tray and wash 6 times with ~ 150 ml TBST for 5 minutes at RT.
1. The blot can now be re-probed by starting at Step 2 in the immunoblotting procedure above.
