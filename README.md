# EcoSentinel

## 🧾 Conclusions

Throughout this project, I explored biodiversity data from U.S. national parks using two datasets: one containing species information and conservation statuses, and another tracking animal observations over a 7-day period. The process involved data cleaning, aggregation, visualization, and statistical analysis.

### 🔍 What I Learned
I learned how to merge multiple datasets, handle missing values, calculate protection rates across species categories, and visualize biodiversity patterns using Matplotlib and pandas. I also implemented a chi-squared test to explore whether certain species types are statistically more likely to be protected.

### 🤔 Were the Results Expected?
Some results were expected — for example, that mammals and birds had high observation counts due to their visibility. However, I was surprised to find that the difference in protection rates between mammals and birds was **not statistically significant**, with a p-value of ~0.688, indicating no meaningful protection bias between them.

### 📌 Key Findings
- The majority of species are not under active conservation intervention.
- **Mammals** had the highest proportion of protected species, though not significantly more than birds.
- **Great Smoky Mountains National Park** had the highest total number of observations.
- A few species dominate sightings across parks, likely due to visibility or abundance.

This analysis can help inform park management and conservation efforts by highlighting trends in biodiversity and the focus of protection efforts. Future steps could include time-series analysis of conservation status changes and integrating habitat or climate data.
