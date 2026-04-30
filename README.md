# Predication-of-Product-Sales
This is a Machine Learning project that is about predicting sales for a specific product of a company
**The process is as follows**
-The data is inspected and cleaned.
-Diagrams and plots are drawn to help better visualize the distribution of data and their relationships

**Different plots in our project were used for different types of data as follows**
- For numeric data, we used Histograms, like this:
<img width="580" height="433" alt="download" src="https://github.com/user-attachments/assets/dc1aaf7e-8de6-49cc-a740-61d3fe8d3b95" />

- For visualizing outliers in the numeric data we used Boxplots, like this:
<img width="576" height="394" alt="download" src="https://github.com/user-attachments/assets/0dcfa1b6-4e35-4b23-b4e2-93309e7e021b" />

- For Categorical data we used Countplots, like this:
<img width="580" height="534" alt="download" src="https://github.com/user-attachments/assets/2c1b2958-7111-4e2b-9c24-0d853ff35317" />

- And for relationships between numeric data, we used heatmaps, like this:
<img width="686" height="589" alt="download" src="https://github.com/user-attachments/assets/2c48c139-71b5-425e-b1d9-2979f6d641a7" />

**Training methods and results**
Two training methods were Used:
1- Linear Regression: The results were lower than the next method
2- Random Forest Regression: The results were better specially after Hyperparameters Tuning using the GirdSearchCV

But over all the model performance was bad, that could be due to the fact that some features had to be removed or the need to process the outliers.
