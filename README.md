# MINFLUX_analysis
This repo contains the code to analyze MINFLUX single molecule tracking data.

The code extracts single molecule tracks from numpy raw track data, overlays individual single molecule tracks on top of the confocal reference channel, categorizes tracks based on subcellular location.

New additions include 5ms rolling window apparent diffusion calculation, calculation of anomalous D exponent alpha as a proxy for confinement, and nanodomain based position density enrichment using KDE. 

