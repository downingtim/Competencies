We examined 53 survey responses spanning 4 levels across each of the 19 competencies. We used R packages data.table v1.16.0 (Barrett et al 2024), dplyr v1.1.4 (Wickham et al 2023), ggplot2 v3.5.1 (Wickham 2016), tidyr v1.3.1 (Wickham et al 2024) and plotly v4.10.4 (Sievert 2020) in R v4.4.1 and RStudio v2024.04.1 (R Core Team 2024) to process and visualise the survey data. Survey responses "Not Applicable" were recoded as zero. We modelled the career stages as a linear series to explore the extent to which these were linearly associated with the competencies' mean scores using Spearman's rank correlation coefficient. We compared each competency's correlation pattern to the mean across all competencies to identify instances where the score exceeded the 95% confidence intervals of the mean trend. We quantified the correlations of each competency pair's scores across the levels. All correlation coefficient p values were Benjamini-Hochberg corrected. In addition, we performed principal components analysis (PCA) on the responses across the levels to explore the extent to which the competencies were correlated with one another. 

Figure 1. The correlation of career stage (x-axes) with mean competency score. The r values denote Spearman's rank correlation coefficient for each competency. The thin coloured lines per plot show the 95% confidence intervals. The black dashed lined is the average correlation pattern across competencies. 

Figure 2. The competencies ranked importance at each career stage with lines representing the change in stages. 

Figure 3. A heatmap of the pairwise correlation of the competencies based on Spearman's rank correlation coefficient. The range is from 0 (blue) to 0.5 (white) to 1.0 (red). The correlation values are shown.

Figure 4. Principal components (PC) analysis of the correlations across the competency data shown across PC1 (accounting for 32% of all variation) and PC (10%). 


References:

Barrett T, Dowle M, Srinivasan A, Gorecki J, Chirico M, Hocking T, Schwendinger B. data.table: Extension of `data.frame`. 2024. https://CRAN.R-project.org/package=data.table

R Core Team. 2024. R: A Language and Environment for Statistical Computing. R Foundation for Statistical Computing, Vienna, Austria. https://www.R-project.org.

Sievert C. Interactive Web-Based Data Visualization with R, plotly, and shiny. 2020. Chapman and Hall/CRC. https://plotly-r.com

Wickham H, François R, Henry L, Müller K, Vaughan D. dplyr: A Grammar of Data Manipulation. 2023. https://CRAN.R-project.org/package=dplyr

Wickham H. ggplot2: Elegant Graphics for Data Analysis. 2016. Springer-Verlag New York. https://ggplot2.tidyverse.org

Wickham H, Vaughan D, Girlich M. tidyr: Tidy Messy Data. 2024. https://CRAN.R-project.org/package=tidyr

