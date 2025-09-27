# faa-flight-delay-analysis
An analysis of FAA flight data to identify causes of delays and cancellations.

## Overview
This project analyzes U.S. FAA flight data to explore factors that contribute to flight delays and cancellations.  
The main objective was to practice data wrangling, statistical modeling, and visualization techniques while working with a real-world dataset.  

The analysis addresses questions such as:
- How does aircraft age relate to delay frequency?  
- Which airlines had the highest ratio of delays and cancellations?  
- What trends can be seen in delay causes (weather, late aircraft, etc.)?  

---

## Dataset
- **Source:** FAA Bureau of Transportation Statistics  
- **Scope:** Domestic flight records (January 2003 dataset used as baseline)  
- **Size:** ~7 million records across multiple fields  

---

## Tools & Technologies
- **R** (RStudio)  
- **tidyverse** for data wrangling (`dplyr`, `tidyr`, `readr`)  
- **ggplot2** for visualization  
- **RMarkdown** for reproducible reporting  
- **caret / glm** for logistic regression  

---

## Methods
1. **Data Cleaning & Transformation**
   - Removed incomplete and duplicate records  
   - Converted categorical variables to factors  
   - Created derived features (e.g., aircraft age from manufacture year)  

2. **Exploratory Data Analysis**
   - Distribution of delays by airline and airport  
   - Visualization of delay ratios  

3. **Statistical Modeling**
   - Logistic regression to test how aircraft age influences delays  
   - Odds ratios to measure strength of predictors  

---

## Results (Highlights)
