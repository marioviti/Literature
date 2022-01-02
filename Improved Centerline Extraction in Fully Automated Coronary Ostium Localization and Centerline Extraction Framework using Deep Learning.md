# Improved Centerline Extraction in Fully Automated Coronary Ostium Localization and Centerline Extraction Framework using Deep Learning

# REVIEW

* WRITING 2/5 poor english)
* METHOD 3/5 Unet only for ostium is op, I'm not huge fan of x,y,z coords regression using U-net, the iterative method is a copy from another pubblication
* VALIDATION 2/5 118 CCTA not bad + CAT08 from Rotterdam dataset, only Validation results are shown on RCA and LCA with no test
* STRENGHT Use of Rotterdam open data, lots of CCTA
* WEAKNESSES Improper repurposing of Unet for coordinate regression (no ablation to validate), no real contribution besides change of hyperparameters of a known architecture (implementation available) lots of data all for training.

# Links
* https://pubmed.ncbi.nlm.nih.gov/34892073/
* https://github.com/marioviti/Literature/blob/main/Improved_Centerline_Extraction_in_Fully_Automated_Coronary_Ostium_Localization_and_Centerline_Extraction_Framework_using_Deep_Learning.pdf
