# Mapping the Income Gap: SNAP vs. Non-SNAP Households in North Carolina

This project analyzes income inequality between SNAP and non-SNAP households across North Carolina counties using 2022 American Community Survey data.  

Using R and spatial analysis techniques, I mapped household income gaps and applied hot-spot analysis (Getis-Ord Gi) to identify regions with statistically significant clustering of high or low inequality.

## Key Findings
- Average income gap of nearly **$40,000** across counties  
- **Hot spots** of high inequality concentrated in the **Piedmont region**  
- **Cold spots** appeared in parts of the coastal and southwestern regions  
- Many counties classified as “insignificant,” showing inequality is **clustered in some regions but dispersed in others**

## Tools & Methods
- **R packages:** tidyverse, tidycensus, sf, spdep, tmap  
- **Techniques:** choropleth mapping, Moran’s I, Getis-Ord Gi, descriptive statistics  
