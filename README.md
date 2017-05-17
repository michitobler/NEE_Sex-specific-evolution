# NEE_Sex-specific-evolution
Supplementary data files from Culumber &amp; Tobler (2017): Sex-specific evolution during the diversification of livebearing fishes. Nature Ecology &amp; Evolution

Zachary W. Culumber (zculumber@gmail.com) and Michael Tobler (tobler@ksu.edu)


"BestMLTree.tre" - The best scoring phylogenetic tree from RAxML.


"250trees.tre" - 250 phylogenetic trees selected randomly from the RAxML bootstrap replicates.


“PredictorVariables.txt" - Variables describing the extent of matrotrophy, variation in sexual selection, and the ecological niche of all species in the analysis.

matroln= Matrotrophy values (natural log transformed); hyphens indicate that data was not available for that species
SSI= Sexual selection index (as established by the extent of sexual dimorphism with each species)
EpPC1-4= First four phylogenetic principal component axes describing the ecological niche based on bioclimatic and hydrological data


“Morphological data.xlsx" - This file contains weight matrices describing body shape variation and measurements of fin size dimorphisms. Note that the file contains multiple spreadsheets:

Weight matrix sex-averaged: Weight matrix describing morphological variation based on sex-averaged phenotypes (species averages were calculated based on male and female data aligned in the same morphospace). The matrix includes 28 partial warp scores and the two uniform components.
Weight matrix females sep: Weight matrix describing female morphological variation in separate morphospace (species averages were calculated based on female data aligned separately without males). The matrix includes 28 partial warp scores and the two uniform components.
Weight matrix males sep: Weight matrix describing male morphological variation in separate morphospace (species averages were calculated based on male data aligned separately without females). The matrix includes 28 partial warp scores and the two uniform components.
Fin dimorphisms: Absolute difference in mean fin measurements between males and females for each species. These values - along with dimorphism in body shape - were used in the calculation of the Sexual Selection Index.
	
	
"NEE Code.TXT" - Basic outline of R code used for phylogenetic comparative analyses.
