# shootings_data_google_trends
Learning pandas through Google Trends by examining how long mass shootings have public attention.

Files:  
* Mother Jones' Investigation- US Mass Shootings, 1982-2016.xlsx - the Mother Jones Data I used as a source  
* Mother_Jones_data.csv - the first worksheet of the above file  
* GTn.csv - the Google Trend data  
* shootings_data_gathering.ipynb - a Jupyter Notebook that contains metadata for all of the csv files from Google Trends. It also contains some previews of the data  
* shootings_topic_dataset.ipynb - a Jupyter Notebook that uses only the data from Google Trends that is a topic (e.g. 'Disaster'). It creates one dataset from the separate csv files. Two files are generates, one that preserves Google Trends' normalization and one that normalizes by maximum value.  
* shootings_fits - a Jupyter Notebook that used the normalized and unnormalized data sets to look at interest in the topics over time
* full_data_unnormalized.csv - the data with Google Trends' normalization preserved  
* full_data_max_normalized.csv - the data normalized by maximum value  
