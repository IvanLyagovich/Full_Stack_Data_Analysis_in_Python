# Full_Stack_Data_Analysis_in_Python
Graphics Cards Ebay Marketplace Analysis.

## Please Note:
Notebook 4: Exploratory Data Analysis and Visualization is not displaying all of the visualizations beacuse GitHub does not support plotly. To view the correct diplay of the notebook please use HTML version.

# Project Overview
Welcome to this repository where a series of Jupyter Notebooks unravel an end-to-end data pipeline process, starting from data collection to data visualization. The project focuses on graphics card data from eBay, aiming to comprehend the correlation between the performance of a GPU model and its price in the eBay market. 

## Notebook 1: Data Collection
The journey begins with this notebook where BeautifulSoup and Selenium come to play to extract information on sold graphics cards from eBay. Details such as the product title, its selling price, additional specifications, the product link, and the date it was sold are meticulously scraped. This data is stored in two accessible formats: as a CSV file and an SQLite database, to ensure flexibility in future analysis.

## Notebook 2: Data Cleaning and Transformation
In the second notebook, the raw dataset undergoes rigorous cleaning and transformation to enhance its usability. The primary aim here is to make the data more understandable and meaningful. Each entry is examined carefully and any inconsistencies or misleading records are diligently addressed.

## Notebook 3: Data Integration and Further Transformation
This third notebook focuses on integrating data from a second source that provides GPU benchmark statistics. The data from eBay listings and the benchmark statistics are merged together based on GPU models, resulting in a more holistic dataset. Once combined, further data cleaning and transformation steps are carried out to ensure data integrity. In the final part of this notebook, a new metric 'performance_score' is introduced which is derived from the GPU's benchmark scores and forms the basis for the subsequent analysis.

## Notebook 4: Exploratory Data Analysis and Visualization
The final notebook delves deep into the exploratory data analysis of the GPU data. The themes around which the exploration revolves include brand and model analysis, condition analysis, and performance analysis. Through comparative studies, relationship mapping, and pattern recognition, the analysis provides a detailed understanding of the dynamics of the GPU market.

# Conclusion
This repository captures the complete journey of data, right from its extraction to the moment it tells a story through visuals. It offers an in-depth look into the GPU market, allowing stakeholders to gain valuable insights for data-driven decision making. The project, however, isn't just about the GPU market. It is also about the journey of understanding the data, treating its flaws, and molding it into a form that not just machines, but even humans can understand. The process implemented here stands as a testament to the flexibility and adaptability of data science. While the content may be GPU-focused, the methodologies and techniques can be applied to any other dataset.
