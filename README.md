# jupyter_for_all_ntsb
JupyterLab utility notebooks for the data munging necessary for the NTSB App for Splunk.

Run from [JupyterLab](https://jupyter.org/) or [Jupyter Notebook](https://jupyter.org/). 

Execute in this order:
1. data_set_download.ipynb - this file downloads the raw data from NTSB; saves file to data folder.
2. data_set_cleanup.ipynb - this file cleans the date format and parses the Location field; saves file to output folder.

Requires the following Python libraries:
1. pandas
2. urllib

Alternatively, if you have no intention of using the Splunk app, you can work with the exploratory data analysis notebook.

Requires the following environmental configuration:
1. conda >= 4.8.3 (or Anaconda3).
2. Visual Studio Code >= 1.44.

How to execute:
1. clone this repository.
2. navigate to the working directory via conda shell (aka Anaconda Prompt).
3. create a new virtual environment: `conda env create -f environment.yml`.
4. activate the new environment with: `conda activate jupyter_for_ntsb`.
5. open the EDA notebook in Visual Studio Code to run: `ntsb_eda.ipynb`