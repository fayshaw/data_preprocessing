[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fayshaw/data_preprocessing/blob/main/livwell.ipynb)

# Data Preproccesing Workshop
## LivWell Dataset: Women and their Well-being for 52 Countries
### Women in Data and PyLadies Boston
August 21, 2025

This code explores LivWell dataset from the Belmin et al's 2022 Nature paper <a href="https://www.nature.com/articles/s41597-022-01824-2">LivWell: a sub-national Dataset on the Living Conditions of Women and their Well-being for 52 Countries</a>. The authors aggregated a longitudinal dataset from Demographic and Health Surveys (DHS) for subnational regions. Much of their work is in geographic harmonization of boundaries.

This code wrangles some of their raw data and compares it to their published data set.  This code was written with the assumption that  people have some experience with pandas dataframes and the google colab or jupyter notebook.  In this notebook, I parse strings, filter data, manipulate dataframes, and visualize data with Plotly.

## How to use
* This code was specifically written for colab.
  * Click on the "Open in Colab" button.
  * Save a copy of the livwell.ipynb to your own Google drive.
* Download the csv files in this repository.
  * The code reads livwell.csv and indicators.csv from urls.
  * The code reads STATcompilerExport_decision_power.csv and GDL-Mean-International-Wealth-Index-(IWI)-score-of-region-data.csv from Google colab file uploads.
