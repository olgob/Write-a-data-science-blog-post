# How to avoid bad wines without particular knowledge on the subject?
 
 ## Library used
The progression of the analysis following the CRISP-DM method is made in a Jupyter Notebook(Python3) environment. 
The following packages are used:
- numpy
- pandas
- matplotlib
- seaborn
- scipy
- nltk
- string
- re
- worldcloud
- PIL
- sklearn

## Motivation of the project
There is so many varieties of wines that it is almost impossible to know them all. Is there any information that we could use to guess the quality of wine even without any particular knowledge?

## Description of the folder / files
- "wines_review_final.ipynb" is the notebook contaning the study following the CRISP-DM method.
- "plot" folder contains all the plots saved from the notebook
- countries_coordinates.txt contains the latitudes and longitude of the countries [countries_csv](https://developers.google.com/public-data/docs/canonical/countries_csv)
- data files are not included in this repository but can be downloaded at the following link : [wine review database](https://www.kaggle.com/zynicide/wine-reviews)

## Result of the analysis
- United States, France and Italy represent 72% of the worldwide production of wines.
- The adjectives used in the description and the description length are good indicators of the wine quality. Moreover, the description length scales linearly with the quality of the wine.
- Even if the higher is the price, the better is the wine on the average, the quality of the wine does not increase linearly of the price. The prices increase drastically for good quality of wine. It is a reason why a linear regression model is not very effective to predict the quality of the wine

## Aknowledgement
The data used comes from a [wine review database](https://www.kaggle.com/zynicide/wine-reviews). 
The result of the study are available on Medium:  [How to avoid bad wines without particular knowledge on the subject?](https://medium.com/p/1a6092b63098/edit)
