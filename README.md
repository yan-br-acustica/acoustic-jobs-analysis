# acoustic-jobs-analysis
This is a very simple routine to generate some insights of current acoustic jobs. The analysis is done in the “analysis.ipynb” file and the used data is in the “vagas_dataset.xlsx” file. 

The database file has the following columns: [“job_title”,”main_field”,”is_in_industry”,”technical_skills”,”soft_skills”,”needed_experience”]. The data on it is composed of keywords based on the raw data from the “Original Posts” folder.

You can gladly improve the database by adding new jobs descriptions, improving the keywords or adding more analysis. 

To run the notebook you need to install the dependencies in “requirements.txt” as: 
```
pip install -r requirements.txt
```
When loading a new project in python, it is always a good practice to create a virtual environment just for the project and install things on it, so you avoid possible dependency conflicts between your libraries (I promise you, this will happen eventually if you use only one environment). This can be done in [Anaconda](https://www.anaconda.com/products/distribution) using the following commands:
```
conda create --name analysis-acoustic-jobs python=3.9
conda activate analysis-acoustic-jobs
pip install -r requirements.txt
```
