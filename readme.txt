This project works in combination with PICARD that uses CoSQL dataset
Clone the PICARD repo from here: https://github.com/ElementAI/picard
Once cloned, goto 'serve.json' file and change 'model_path' attribute's value to "tscholak/2jrayxos"
Now, Install conda from here https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html
Create a conda version for this project. More info here: https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html
Then, goto 'CoSQL_ncNet.ipynb' in ncNet and change the kernel from the top right to the conda version you created in the above step
Download datasets from here 1. https://www.kaggle.com/imdevskp/covid19-corona-virus-india-dataset?select=district_level_latest.csv  2. https://www.kaggle.com/fireballbyedimyrnmom/us-counties-covid-19-dataset
In the third cell of 'CoSQL_ncNet.ipynb' provide the csv location of the above datasets
'CoSQL_ncNet.ipynb' contains various cells which could be run independently. You should start running them top which imports necessary libraries
You now run various examples present in 'CoSQL_ncNet.ipynb'
