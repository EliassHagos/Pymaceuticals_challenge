# Pymaceuticals_challenge

ELIAS HAGOS
05/18/2023

The provided code performs a comprehensive analysis of a medical study on mice. It begins by loading and cleaning the data, merging the mouse metadata and study results into a single DataFrame. Duplicated mouse IDs are identified and removed from the dataset. Summary statistics, including mean, median, variance, standard deviation, and standard error of tumor volume, are calculated for each drug regimen, resulting in a DataFrame called summary_stat.

The code also visualizes the data through informative plots. A bar plot showcases the number of mice tested per treatment, while a pie chart displays the distribution of female and male mice. Additionally, box plots are created to depict the final tumor volume for each drug regimen, offering insights into potential outliers. 

A line plot illustrates the tumor volume over time for a specific mouse. Furthermore, a scatter plot shows the relationship between weight and average tumor volume for the drug regimen "Capomulin," with a linear regression line providing further analysis. The code concludes by printing the correlation coefficient between weight and tumor volume for the "Capomulin" regimen. Overall, these analyses and visualizations offer valuable insights into the medical study's data, aiding in the interpretation and understanding of the results.