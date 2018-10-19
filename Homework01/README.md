**TASK01**: The `Data/ebola` folder contains summarized reports of Ebola cases from three countries (Guinea, Liberia and Sierra Leone) during the recent outbreak of the disease in West Africa. For each country, there are daily reports that contain various information about the outbreak in several cities in each country. Use pandas to import these data files into a single `Dataframe`. Using this `DataFrame`, calculate for each country, the daily average per month of new cases and deaths. Make sure you handle all the different expressions for new cases and deaths that are used in the reports.

**TASK02**: In the `Data/microbiome` subdirectory, there are 9 spreadsheets of microbiome data that was acquired from high-throughput RNA sequencing procedures, along with a 10th file that describes the content of each. Use pandas to import the first 9 spreadsheets into a single `DataFrame`. Then, add the metadata information from the 10th spreadsheet as columns in the combined `DataFrame`. Make sure that the final `DataFrame` has a unique index and all the `NaN` values have been replaced by the tag `unknown`.

**TASK03**: Use pandas to import the data file `Data/titanic.xls`. It contains data on all the passengers that travelled on the Titanic. For each of the following questions state clearly your assumptions and discuss your findings:
1. Describe the type and the value range of each attribute. Indicate and transform the attributes that can be Categorical.
2. Plot histograms for the travel class, embarkation port, sex and age attributes. For the latter one, use discrete decade intervals.
3. Calculate the proportion of passengers by cabin floor. Present your results in a pie chart.
4. For each travel class, calculate the proportion of the passengers that survived. Present your results in pie charts.
5. Calculate the proportion of the passengers that survived by travel class and sex. Present your results in a single histogram.
6. Create 2 equally populated age categories and calculate survival proportions by age category, travel class and sex. Present your results in a `DataFrame` with unique index.
