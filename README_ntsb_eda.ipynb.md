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