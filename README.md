# Wage_Prediction
Jupyter Notebook explorando e criando modelo de classificação dataset com dados socieconômicos para predição de renda anual de pessoas.
Jupyter Notebook exploring and creating classification models from a dataset with socioeconomic data for predicting people's annual income.

Download the Indicium_DS.ipynb. You can run it at a Jupyter Notebook with Python 3 or in a in Google Colab.
The file was created using Python 3.8.8

For Jupyter Notebook:
Download wage_train.csv and wage_test.csv. Save them at the same directory as Indicium_DS.ipynb.
Open Indicium_DS.ipynb with the Jupyter Notebook and run all the cells.

For Google Colab:
Download wage_train.csv and wage_test.csv. Upload them into google colab using the left menu on the colab screen, clicking in Files and dragging both csv's.
Edit the first cell to get the following:

#path_train = 'wage_train.csv' # For Jupyter Notebook
#path_test = 'wage_test.csv' # For Jupyter Notebook

path_train = '/content/wage_train.csv'#For google Colab
path_test = '/content/wage_test.csv'#For google Colab

from google.colab import drive
drive.mount('/content/drive/',force_remount=True)

Run all the cells.
