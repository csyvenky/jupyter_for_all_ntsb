# jupyter_for_all_ntsb
JupyterLab Notebook for cleaning up NTSB dataset.

Run from [JupyterLab](https://jupyter.org/) or [Jupyter Notebook](https://jupyter.org/). Execute in this order:
1. data_set_download.ipynb - this file downloads the raw data from NTSB; saves file to data folder.
2. data_set_cleanup.ipynb - this file cleans the date format and parses the Location field; saves file to output folder.

Requires the following libs:
1. pandas
2. urllib
