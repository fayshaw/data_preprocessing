[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fayshaw/data_preprocessing/blob/main/livwell.ipynb)

# Data Preproccesing Workshop
## LivWell Dataset: Women and their Well-being for 52 Countries
### Women in Data and PyLadies Boston
August 21, 2025

This code explores LivWell dataset from the Belmin et al's 2022 Nature paper <a href="https://www.nature.com/articles/s41597-022-01824-2">LivWell: a sub-national Dataset on the Living Conditions of Women and their Well-being for 52 Countries</a>. The authors aggregated a longitudinal dataset from Demographic and Health Surveys (DHS) for subnational regions. Much of their work is in geographic harmonization of boundaries.

This code wrangles some of their raw data and compares it to their published data set.  This code was written with the assumption that  people have some experience with pandas dataframes and the google colab or jupyter notebook.  In this notebook, I parse strings, filter data, manipulate dataframes, and visualize data with Plotly.

## How to use
* This code was written using colab.
  * Click on the "Open in Collar" button.
  * Save a copy of the livwell.ipynb to your own Google drive.
* Files
  * Download the files STATcompilerExport_decision_power.csv and GDL-Mean-International-Wealth-Index-(IWI)-score-of-region-data.csv from Google colab file uploads.
  * This code reads livwell.csv and indicators.csv from urls.

# About the LivWell dataset

## Code 
The authors provided their R package to access their LivWell dataset <a href="https://gitlab.pik-potsdam.de/belmin/livwelldata">https://gitlab.pik-potsdam.de/belmin/livwelldata</a> and their code to reproduce findings of their paper in <a href="https://gitlab.pik-potsdam.de/belmin/livwelldata-paper/">https://gitlab.pik-potsdam.de/belmin/livwelldata-paper/</a>.


## Citation
Belmin, C., Hoffmann, R., Elkasabi, M. et al. LivWell: a sub-national Dataset on the Living Conditions of Women and their Well-being for 52 Countries. Sci Data 9, 719 (2022). https://doi.org/10.1038/s41597-022-01824-2

## Creative Commons
This is an open access article distributed under the terms of the Creative Commons CC BY license, which permits unrestricted use, distribution, and reproduction in any medium, provided the original work is properly cited.