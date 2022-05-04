# Analysis of COVID-19’s Impact on Foot Traffic in Charleston

Using mobile phone data collected anonymously by Safegraph for the Charleston-North Charleston, SC Metro Area from January 1, 2018, until February 14, 2022, I analyzed COVID-19’s impact on the Charleston-North Charleston Metro Area by comparing foot traffic from 2019 to 2020 and then to 2021. I attempted to build K-Means clustering models for each season (Winter, Spring, Fall, and Summer) that could predict a week of foot traffic in Charleston based on the previous week. The SafeGraph dataset contains weekly patterns for each location in Charleston, including visit counts broken down by day and hour and information about the people visiting each location, such as the neighborhood they live in and other locations they visit.  My model and analysis provides insight into how COVID-19 has impacted foot traffic in Charleston, SC, USA. This GitHub contains the code used to preprocess the data and create the model and visualizations.

1. To run the models in this project, you will need access to the scikit-learn libraries and Ts-learn. This can be installed through pip or conda install.
2. Download all the files. Make sure the csv files are saved in the same folder as the Jupyter Notebook files.
3. Open  COVID_Data_Pre-Processing.ipynb in Jupyter Notebook. This file contains the steps I took to do preprocess the data. It will output a file called processed_data.csv. This file is also available for download if the file does not work as expected.
4. Next, open  COVID_Modelling.ipynb in Jupyter Notebook. This is the file I used to build and test my models as well as create some of the visualizations.
5. The last file, Visualization.ipynb shows how I created the first graph in the research paper.


## Authors

* **Jane Shelby Porter**


## Acknowledgments

* Dr. Navid Hashemi at the College of Charleston for all of his help.
* SafeGraph
