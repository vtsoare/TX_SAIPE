# TX_SAIPE
This repository will contain Jupyter notebooks demonstrating aspects of data analysis using the 2020 SAIPE data for Texas. 
The SAIPE survey estimates poverty rates in the US and is organized by state and then by county.

The data I use pertains to the state of Texas, and can be found at https://www2.census.gov/programs-surveys/saipe/datasets/2020/2020-state-and-county/est20-tx.txt
The technical documentation for the data can be found at https://www2.census.gov/programs-surveys/saipe/technical-documentation/file-layouts/state-county/2020-estimate-layout.txt

In the first notebook, TS_Clean, I download the data and clean it up, fixing some formatting issues that arised from the original data being a TXT file, and adding column names. I also save the file to be used later. 
In the next notebook, TS_Vis, I create some visualization to better understand the data, namely I compare the percentage poverty by the three categories in the dataset, as well as mapping the general poverty percentage by county. This notebook might be modified in the future to add more visualizations.
