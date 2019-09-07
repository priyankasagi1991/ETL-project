# ETL-project

![Image of Dog](http://www.clker.com/cliparts/c/2/8/f/15163317901114816206free-clipart-dog-days-of-summer.med.png)
   
   The purpose of our database is to aggregate information with regard to different dog breeds and their respective obedience scores   The data was downloaded and stored locally as a csv file (https://data.world/len/dog-size-intelligence-linked/workspace/file?filename=dog_intelligence.csv).    The data was cleaned by removing non-relevant columns in Jupyter notebook.    The cleaned data frame containing the dog breed, classification, and obedience score was loaded into a postgresql database.
    
    
  Data Set 1- “2017 Dog” Dataset:
    
   Data was harvested from Kaggel.com @ https://www.kaggle.com/kingburrito666/largest-dog-breed-data-set. The first decision we made was to identify which columns were relevant for our purpose, hence should be kept and which ones were irrelevant to our purpose and should be excluded. The Dog Breed, Dog name and Dog color were selected as the most relevant and included in the new dataset.
    
    
  AKC (American Kennel Club) Dog Breed Dataset:
    
   The purpose of our database is to aggregate information with regard to different dog breeds and their respective size (height). The data was downloaded and stored locally as a csv file (https://data.world/len/dog-size-intelligence-linked/workspace/file?filename=AKC+Breed+Info.csv). Within the csv, there were special characters, which were causing the file to not be readable. These characters were removed before importing the csv into our Jupyter notebook. The data was cleaned by removing non-relevant columns in Jupyter notebook. The cleaned data frame containing the dog breed and dog height was loaded into a postgresql database. Worked on by Eddy and Kingsford.
