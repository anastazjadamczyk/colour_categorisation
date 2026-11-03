# Colour categorisation scripts

The repository contains scripts that we used to categorise the colours chosen by participants in the Perception Census project (ref.), Colour Preference task. 
It is supporting material for the study: 
Adamczyk, A., Mohr, C., Dan-Glauser, E., & Jonauskaite, D. (2025). Registered report protocol for the Perception Census: Linking colour preferences and colour-emotion associations. In principle acceptance of Version 3 by Peer Community in Registered Reports. https://osf.io/wdqab. 

Participants chose colours from an unrestricted colour range. Their choices were saved as RGB values and then converted into CIE LCh using the R studio farver package (Pedersen et al., 2024).

The thresholds were derived from the study by Parraga et al. (2016) and were further adjusted based on visualisation of a large independent dataset with colour preference data (N = 8,302; Ouznadji et al., 2026).

colour_categorisation_script.R is the pre-registered script
colour_categorisation_script_updated.R is the updated version, with improved thershold values for the BLUE/PURPLE border. 

Visualisations of both categorisations are availible in the folders: cat_visualisations_oldthresh, for pre-registered threshold values and cat_visualisations_newthresh for the corrected, updated values

