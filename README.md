# Analysis
* Concatenate the two tables of the problem 1 dataset - https://www.kaggle.com/datasets/braindeadiiest/brain-dead-rice-production-data-in-india?rvi=1
* Run the notebook **[ps1_data_preprocessing.ipynb](ps1_data_preprocessing.ipynb)** on this concatenated csv file to obtain **[processed_ds1.csv](processed_ds1.csv)**
* The jupyter notebook **[Problem1Analysis_EDA.ipynb](Problem1Analysis_EDA.ipynb)** is used for all the analysis tasks. Run this notebook on **[processed_ds1.csv](processed_ds1.csv)** file for EDA.

* For creating **[Cluster Map of Rice Production](clustermap.ipynb)**  we needed data such that it doesnot contain any NaN values neither any empty values, one approach was to replace those cells with the column mean but for this analysis we used **[processed_ds1_telengana_predicted.csv](processed_ds1_telengana_predicted.csv)** where by analysing the future trends of the state earlier values have been predicted.

# Forecast
* Run the notebook **[Forecast_without_AP&Telangana.ipynb](Forecast_without_AP&Telangana.ipynb)** on **[processed_ds1.csv](processed_ds1.csv)** to forecast rice production of all states except Andhra Pradesh & Telangana for the next 5 years (2023-28).
* Run the notebook **[AP_+_Telangana_Rice_Prod_Forecast.ipynb](AP_+_Telangana_Rice_Prod_Forecast.ipynb)** on **[processed_ds1.csv](processed_ds1.csv)** to forecast rice production of Andhra Pradesh & Telangana for the next 5 years (2023-28). This notebook also has script to obtain plots of forecast.

# External Dataset
* Run the notebook **[External_Dataset/rice.ipynb](External_Dataset/rice.ipynb)** on **[External_Dataset/rice_aggregated_2004_2020.csv](External_Dataset/rice_aggregated_2004_2020.csv)** to analyse how rice production is affected by external factors such as rainfall etc.
