# MaltBarley_GroundtoGlass
Supporting data and R code for Craine et al., 2022 (https://doi.org/10.3390/beverages8020030)

## Supplementary Materials:
The following are included and are available online at https://www.mdpi.com/article/10.3390/beverages8020030/s1
- Table  S1 (**Beverages_G2G_S1.xlsx**)
  - Experimental  malting  conditions  of  field  replicates  bythe uniform method (conducted by the United States Department of Agriculture [USDA] CerealCrops Research Unit [CCRU], Madison, WI, USA) and the modified method (conducted by theHartwick College Center for Craft Food and Beverage, Oneonta, NY, USA)
- Table S2 (**Beverages_G2G_S2.pdf**)
  - Commercial-scale malting conditions for the genotype, as performed by Gold Rush Malting, LLC. Baker City, OR,U.S.A
- Table S3 (**Beverages_G2G_S3.xlsx**)
  - Respondent characteristics from the consumer survey
- Table S4 (**Beverages_G2G_S4.csv**)
  - Respondent datafrom the sensory evaluation
- Table S5 (**Beverages_G2G_S5.xlsx**)
  - Malt quality data for each genotype, as malted by Gold RushMalting LLC.
- Table S6 (**Beverages_G2G_S6.xlsx**)
  - Replicated (n= 3) grain and malt quality data for each genotype using themodified method
- Table S7 (**Beverages_G2G_S7.xlsx**)
  - Replicated (n= 3) grain and malt quality data for each genotype usingthe standard method.

## Files

### Craine_G2G_Rank_FriedmansNemenyi.xlsm
- Beer Rank Analysis (Figure 1)
- XLSTAT
### Craine_G2G_CATA.xlsm
- CATA analysis of attributes with approximately 5 citations or more
### Craine_G2G_DescCoded.xlsm
- Open description analysis of attributes with approximately 5 citations or more
### Craine_G2G_NewDesc.xlsm
- Novel terms (i.e. new description) analysis of attribtues with approxixmately 5 citations or more
### Craine_G2G_MaltQuality.Rmd
- Questions
  - How does field replicate, entry, and maltster influence malt quality traits for experimental and commercial malts?
  - How are malt quality traits related?
- requires
  -  **2018_hartwick_GoldRush_unreplicated_working.csv**
  -  **2018_MaltQuality_CCRU_Hartwick_repped_Cleaned.csv**
  -  **2018_CCRU_repped_cleaned.csv**
### Craine_G2G_MaltQuality_Rank.Rmd
- What is the relationship between malt quality of commercial malt (Gold Rush) and beer rank?
- requires
  - **2018_hartwick_GoldRush_unreplicated_working.csv**
  - **BF_maltQuality_Rank.csv**
### Craine_G2G_screenerRankCATA.Rmd
- Analysis of Screener, Rank, Open Description and CATA
- requires
  - **BF2_Round2_wDesc.csv**
  - **BF_Round2_Questionnaire.csv**
  - **BF.Rank.Wide.csv**
  - **BF2.CATA.binary.uniqueID.csv**
  - **BF2_CATA_all.csv**
  - **BF_CATA_ContingTable_Filter5Out.csv**
  - **BF2_CATAFilter5Out_Rank.csv**



