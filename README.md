   ### The First Step in Oncogenicity Determination - Predict the effect of Genetic Variants on Protein Function

  The data can be downloaded directly form Kaggle at:

  https://www.kaggle.com/c/msk-redefining-cancer-treatment/data


  Additional gene function and pathway information were down loaded "Database for Annotation Visualization and Integrated Discovery"(DAVID ) to a david_full.csv file and is included in the submissions. 

  The code generates the gene summary info form National Center for Biotechnology Information(NCBI). A gene symbol / gene name /gene id conversion function on the david website was used. The unique gene symbol/ name / id is include in the gene_id.csv

  The Udacity 'aind'  environment was used. 

  An additional library was used: 

  http://biopython.org/

  biopython was used and from Bio 'Entrez' was imported

  This was difficult to set up.

  The jupyter notebook should be able to run now top to bottom with running the additional biological code.

  The Capstone report is a pdf. The code to reproduce all results and images are in a jupyter notebook. Since the additional libraries were difficult to set up, all related code for the additional biological data is commented out so the jupyter notebook can be run easily from top to bottom. This will produce all other results. The pdf report will have information about the additional biological data. 

  This was difficult to set up.

  If you choose to run the additional biology data code follow these directions:

  install biopython 
  form Bio install Entrez

  Uncomment all commented out code. 

  Gene id was needed to search the ncbi website. The given data was in gene name. Luckily  the biological website david.com has a conversion function. So I created a uniq_genes.csv  up loaded it to the david site and it covered the gene names to gene id and it was downloaded to my computer as gene_ids.csv. This file is also included in my submission. The Entrez web site were I did a search required my email address. This is in my code. If you chose to run the additional biology code you may need to change this to your email. I think it should work with my email.

  The david_full.csv, gene_ids.csv and the input data file(from kaggle, the address is above) all need to be in the same directory as the jupyter notebook. If the biological data is not run only the input file from Kaggle is needed.





