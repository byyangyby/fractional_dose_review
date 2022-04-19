# Review of dose fractionation of COVID-19 vaccines

This reposory contains data and R scripts that were used for the preprint entitled **"Immunogenicity, efficacy, and safety of SARS-CoV-2 vaccine dose fractionation: a systematic review and meta-analysis"** by Yang B, Huang X., Gao H., Leung N.H., Tsang T.K. and Cowling B.J..

Correspondance regarding this study shall be addressed to Benjamin Cowling (bcowling@hku.hk) or Bingyi Yang (yangby@hku.hk).

## Data

All data were extracted and summaized from published studies, with detailed can be found in file *References*. 

1) *data_seroconversion.csv* - Contains data used to examine differences in the proportion of seroconversion of nAbs after recieving fractional and standard dose groups.
2) *data_nAbs.csv* - Contains data used to estimate dose-response relationships between dose fracnation and nAbs levels.
3) *data_ve_agg.xlsx* - Contains data of cross-reactions between variants and the projected vaccine effecicacy of complete vaccinations of half-dosages.
4) *data_ve_variants.xlsx* - Contains empirical data of vaccine effectiveness of COVID-19 vaccines against variants, which were used for validating projected vaccine efficacies.
5) *data_t_cell.csv* - Contains data to compare T-cell immunity between fractional dose groups and pre-vaccnation levels and standard dose groups.
6) *data_safety.csv* & *data_safety_agg.xlsx* - Contains data used to compare safety profiles after recieving fractional and standard dose groups.


## Analysis

R scripts that were used for main and supplementary analysis can be found in *Fractional_doses.Rmd*.
