# Hwang-2024-MycotoxinMaizeFieldCondition

## Overview
Aflatoxin contamination in post-harvest maize threatens food safety and security; therefore, there is a value in finding ways to reduce mycotoxin contamination in maize. Our study focused on using a pre-calibrated multi-spectral sorting machine based on visual characteristics previously associated with mycotoxin contamination of maize kernels to reduce aflatoxin contamination in maize. Maize samples (n=45 each) were collected from Ghana and Kenya. A pre-existing linear discriminant analysis (LDA) classification algorithm was used to reject kernels with high visual risk features. 5g subsamples of the sorted samples were used for a one-step lateral flow immunochromatographic assay and ELISA for Ghana and Kenya samples, respectively. After sorting, aflatoxin mean difference between the accept and the reject stream for Ghana was -0.28 log(ng/g), paired t-test showed significant difference (p<2.2e-16) between the accept and reject levels for each individual sample . Kenya sample’s mean difference was -0.28 log(ng/g) (p=0.08 by paired t test ). The Ghana and Kenya samples had an average mass rejection of 37.9% (range 15.9-10.7), 7.17% (range 1.10-25.2%) respectively. This shows that performing multi-spectral sorting under less controlled field conditions still retained efficacy to reduce mycotoxin in maize, despite having a lower effect than when aflatoxin sorting performed under highly controlled laboratory settings.

## Usage
### Setup
Data analysis was performed in [R 4.4.1](https://cloud.r-project.org/) and [RStudio Desktop](https://posit.co/download/rstudio-desktop/) with the following packages:
* BayesianReasoning
* car
* datasets
* data.table
* gapminder
* ggplot2
* ggpubr
* grid
* gridExtra
* multcompView
* patchwork
* plotly
* reshape2
* ragg
* rstatix
* tidyverse

### Running
Data and code are located in "data and analysis".

R analysis can be run by opening the "data and analysis.Rproj" file, followed by "Julie_Ghana_Kenya_revised.Rmd" and running the required code chunks.

## Authors
You can view the list of authors in the [AUTHORS](/AUTHORS) file.

## Contact
Corresponding author: Matthew J. Stasiewicz<br>
103 Agricultural Bioprocess Lab<br>
1302 W. Pennsylvania<br>
Urbana, IL, 1361801<br>
USA<br>
+1-217-265-0963<br>
[mstasie@illinois.edu](mailto:mstasie@illinois.edu)

## Citation
Publication pending.

## License
This project's code is licensed under the GNU General Public License v3.0 and dataset is licensed the Creative Commons Attribution Share Alike 4.0 International license. Please see the [LICENSE.code](/LICENSE.code) and [LICENSE.dataset](/LICENSE.dataset) files for details.

## Funding
This work was supported by the University of Illinois at Urbana‐Champaign College of Agriculture, Consumer and Environmental Sciences (ACES) Office of International Programs seed grant to Matthew J Stasiewicz, and Global Food Security Internship Program to Julie Hwang. As well as an ACES James Scholar Honors Program travel grant to Julie Hwang. As well as a University of Illinois I-MMAS program and Tecnológico de Monterrey partnership research internship to Mauricio Canales. As well as a USDA Research Capacity Fund (Hatch) project Food and Nutrition Systems for Safety, Security and Sustainability [ILLU-698-930] to Matthew J Stasiewicz.
