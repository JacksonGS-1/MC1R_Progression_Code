# MC1R_Progression_Code
Project Title: MC1R loss-of-function is associated with accelerated motor progression in Parkinson’s disease 

Project Overview: Included in this repository is the R and SAS code used to analyze longitudinal clinical data from PD and prodromal PD participants in the Parkinson's Progression Markers Initiative (PPMI). In order to analyze different clinical parameters simply rename "updrs" to the parameter of interest. 

Dependencies: The data required to run this code can be found in the PPMI Database (www.ppmi-info.org/access-data-specimens/download-data; RRID:SCR00_6431). After downloading and curating the data from PPMI, simply update the working directory and file paths to run this code. The following R packages are required to run this code: dplyr, readxl, tableone, writexl, tidyr, VennDiagram, grid, lme4, lmerTest, ggplot2, sjPlot, broom.mixed, patchwork, ggpubr, RColorBrewer, vcd. 

Installation: All dependencies will be automatically installed when running this code. 

Citation: cff-version 1.2.0
- Type: Software
- Authors:
  - Jackson G. Schumacher
  - Email: jgschumacher@mgh.harvard.edu
  - Affiliation: >-
      Aligning Science Across Parkinson's and Massachusetts
      General Hospital
  - ORCID: https://orcid.org/0009-0000-4227-4710
  - Xinyuan Zhang
  - Email: hpxzh@channing.harvard.edu
  - Affiliation: Harvard Medical School
  - ORCID: https://orcid.org/0000-0002-2974-8392
- License: CC-BY-4.0

Acknowledgements: This research was funded in part by Aligning Science Across Parkinson's No. ASAP-237603 through the Michael J. Fox Foundation for Parkinson's Research (MJFF) and by the National Institute of Health through the National Institute of Neurological Disorders and Stroke grants R01NS102735 and 5R01NS126260. The authors would like to thank PPMI – a public-private partnership – funded by the Michael J. Fox Foundation for Parkinson's Research and funding partners, including 4D Pharma, Abbvie, AcureX, Allergan, Amathus Therapeutics, Aligning Science Across Parkinson's, AskBio, Avid Radiopharmaceuticals, BIAL, BioArctic, Biogen, Biohaven, BioLegend, BlueRock Therapeutics, Bristol-Myers Squibb, Calico Labs, Capsida Biotherapeutics, Celgene, Cerevel Therapeutics, Coave Therapeutics, DaCapo Brainscience, Denali, Edmond J. Safra Foundation, Eli Lilly, Gain Therapeutics, GE HealthCare, Genentech, GSK, Golub Capital, Handl Therapeutics, Insitro, Jazz Pharmaceuticals, Johnson & Johnson Innovative Medicine, Lundbeck, Merck, Meso Scale Discovery, Mission Therapeutics, Neurocrine Biosciences, Neuron23, Neuropore, Pfizer, Piramal, Prevail Therapeutics, Roche, Sanofi, Servier, Sun Pharma Advanced Research Company, Takeda, Teva, UCB, Vanqua Bio, Verily, Voyager Therapeutics, the Weston Family Foundation and Yumanity Therapeutics. 
