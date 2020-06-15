# matplotlib-challenge: The Power of Plots

## Background 

249 mice identified with squamous cell carcinoma (SCC) tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. The task was to generate all of the tables and figures needed for the technical report of the study, as well as a top-level summary of the study results.

* The script was coded using Jupyter notebook. The libraries used were Pandas, Matplotlib, NumPy and SciPy.

* All files are inside the folder named for the challenge `Pymaceuticals`. This folder contains:

    * A Jupyter notebook called `pymaceuticals.ipynb` to run the analysis. The notebook also contains observations and insights that were made looking at the data and calculations (this is also below under *Analysis*).

    * A `data` folder that contains the CSV files `Mouse_metadata.csv` and `Study_results.csv`. 


## Analysis

* There appears to be an almost equal distribution of female to male mice in the overall study, with female mice at 49.6% and male mice at 50.4%.

* From the box plot and quartile calculations of the four promising drug treatments, it is shown that the only drug regimen to have any outliers is Infubinol, with only one data point outside the lower boundary of 36.83. This shows that the statistical distribution of data is normal.

* The box plot also indicates that the mean and median values, as well as the interquartile ranges and boundaries of the Capomulin and Ramicane treatments are lower than those of Infubinol and Ceftamin. These results suggest that Capomulin and Ramicane were more successful in treating tumors and appear to have had the best results, with the final tumor volumes being much lower than the other two.

* Capomulin's positive effects are further shown in the line plot where we see the tumor volume for mouse test subject 's185' reduced by almost half at the end of the study.

* The scatterplot and linear regression model shows us a strong positive correlation (0.84) between average tumor volumes and mouse weights in the Capomulin treatment. This indicates that on average, the bigger the mouse, the larger the tumor.

