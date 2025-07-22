# Yelp LA Restaurant Reviews: Text Analytics Project
**Group Members:** Leah, Caleb, Tami, and Maddie  
**Course:** MKTG 6640 – Text Analytics  
**Semester:** Summer 2025

This project analyzes Yelp reviews for the Top 50 and Bottom 50 ranked restaurants in Los Angeles to identify differences in customer sentiment, key themes, and distinguishing characteristics of highly rated establishments.

---

## Instructions for Running the Code

1. Open the RMarkdown file: `Group1_Project.Rmd`
2. Knit to HTML or PDF by clicking the "Knit" button in RStudio.
3. Ensure all required packages (listed below) are installed prior to knitting.
4. All file paths are currently local. Update them if needed (e.g., for the CSV file or outputs).
5. If errors occur during PDF knitting, switch to HTML or check for encoding issues (e.g., Unicode characters like `→` or `–`).
6. Final outputs will include:
   - Cleaned dataset with RankGroup labels
   - TF-IDF analysis
   - Sentiment visualizations
   - Topic modeling
   - Word embedding PCA plots
   - Summary insights

---

## Required Libraries

```r
library(tidyverse)
library(tidytext)
library(tm)
library(textdata)
library(syuzhet)
library(tokenizers)
library(textstem)
library(wordcloud)
library(topicmodels)
library(SnowballC)
library(ggplot2)
library(gridExtra)
library(patchwork)
library(lubridate)
library(knitr)
library(readr)
library(stringr)
library(tidyr)
library(widyr)
library(quanteda)
library(quanteda.textmodels)
library(quanteda.textplots)
library(text2vec)
library(text)
library(irlba)
library(scales)
```

You can install any missing packages using `install.packages("package_name")`.

---

## Citations & References

- Yelp Dataset: Extracted via internal tool from Yelp’s public-facing review pages (for educational use).
- Sentiment Lexicon: Bing Liu’s Opinion Lexicon via `textdata` and `syuzhet` packages.
- Topic Modeling: Based on Blei et al. (2003) Latent Dirichlet Allocation.
- Embeddings: Pretrained GloVe model from `text2vec`.
- PCA & TF-IDF: Implemented using standard `tidytext`, `text2vec`, and `ggplot2` methodologies.

**Resources:**
- Silge, J., & Robinson, D. (2017). *Text Mining with R*. O’Reilly Media.
- tidytext documentation: https://www.tidytextmining.com/
- text2vec documentation: https://cran.r-project.org/web/packages/text2vec/

---

## Project Files

The following files are included in the project submission:

- `Group1_Project.Rmd` – Full RMarkdown code notebook
- `Group1_Project.knit.html` – HTML output of analysis
- `Group1_Final_Report.pdf` – Written report of findings
- `MKTG 6640 Final Project - Group 1.pdf` – Final slide deck presentation
- `top 240 restaurants recommended in los angeles 2.csv` – Yelp review dataset

Make sure all files are saved in the same working directory for full reproducibility.



