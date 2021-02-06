# Cytokine Compartment Analysis
> Exploratory analyses to determine association between smoking status/ cotinine concentrations and cytokine concentrations.

> All cytokine compartment analyses in this folder are designated by their figure number or table number in the manuscript in parantheses.



## Cluster Distribution Comparison (Table S5)
- Used ANOVA test as a crude model (serving as similar function as original Wilcoxon Rank Sum tests) to compare ANCOVA results. ANCOVA was run to control for age (Table S3). This is the same analysis in the cytokine distribution comparison, but now we are comparing clusters of cytokines rather than individual cytokines.
   
## Baseline Analysis (Figure 1 and Figure S1)
- Calculating and visualizing mean and standard deviation of baseline (non-smokers) concentrations for each cytokine (Figure 1). 
- Running Shapiro-Wilk's test for normality between each compartment (NLF, ELF, Sputum, or Serum) at baseline. 
- Calculating and visualizing median and standard deviation of baseline (non-smokers) concentrations for each cytokine (Figure S1). 

## Simulation Analysis (Figure 2)
- Simulated 500 concentration data points to see if randomly generated data would yield similar statistically significant and highly correlated results between each across compartmental analysis. 

## Cluster Visualization (Figure 3)
- Visualizing clustered eigencytokines by compartment
- Note that this version isn't in the manuscript!

## Cytokine Demographics Distribution Comparison (Table S6)
Running Wilcoxon Rank Sum tests and stratifying subjects based on the demographic variable of interest (race, ethnicity, sex, age, or bmi) further stratifying compartment to determine how cytokine distributions varied for each variable. 


## Demograhic Eigencytokines & Clustered Demographics Distribution Analysis (not in manuscript)
- Based on the results from the 'Cytokine Demographics Distribution Comparison',  eigencytokines were found using male subjects only followed by running Wilcoxon Rank sum tests between male non-smokers and e-cigarette users. 
- <i> For clarification, this version isn't in the manuscript. This was done to QC code that was previously written. </i>
