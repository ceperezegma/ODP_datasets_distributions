# what is it about?
this repo contains a set of jupyter notebooks for automatic processing of the dataset about the datasets files formats published in the [EU open data portal (ODP)](https://data.europa.eu/euodp/en/data). The dataset comes from an daily automatic extraction of the number of datasets file formats available in [this google sheet](https://docs.google.com/spreadsheets/d/1L3jZ1lhESQEpdiU7Vd1BY9YvJ4KO0Po-sPEfhCfEKuI/edit?usp=sharing). 

# data source - input
the input dataset is coming from the source: [datasets files formats](https://docs.google.com/spreadsheets/d/1L3jZ1lhESQEpdiU7Vd1BY9YvJ4KO0Po-sPEfhCfEKuI/edit#gid=1686327626)

# data processing
the processing in this notebook manage different cases: 
* data cleansing
* data reshaping
* data aggregation per dataset file format

# processing notebooks
There are 2 notebooks:
* ODP_datasets_formats.ipynb: notebook to use for the processing of all the stored data in the [google sheet](https://docs.google.com/spreadsheets/d/1L3jZ1lhESQEpdiU7Vd1BY9YvJ4KO0Po-sPEfhCfEKuI/edit#gid=1686327626)
* ODP_datasets_formats_update.ipynb: notebook to use for the processing new data available in the [google sheet](https://docs.google.com/spreadsheets/d/1L3jZ1lhESQEpdiU7Vd1BY9YvJ4KO0Po-sPEfhCfEKuI/edit#gid=1686327626) since the last time the data was processed.

# processed data files - output
there are 4 CSV files: 
* datasets_formats_processed.csv: output file containing the data processed.
* processed_dates_update.csv: output file tracking the processed dates.
* datasets_formats_processed_backup.csv: copy of the previous output file containing the data processed.
* processed_dates_update_backup.csv: copy of the previous output file tracking the processed dates.
