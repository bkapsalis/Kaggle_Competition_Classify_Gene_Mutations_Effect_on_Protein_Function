  ## The First Step in Oncogenicity Determination - Predict the effect of Genetic Variants on Protein Function

  Click above Capstone.pdf to see report.
  Click above Capstone_mlnd_Unabriged_all_code_very_long.ipynd to see report including all code.


  Additional gene function and pathway information were down loaded from "Database for Annotation Visualization and Integrated Discovery"(DAVID) to a david_full.csv file and is included in the submissions. 

  The code generates the gene summary info form National Center for Biotechnology Information(NCBI). A gene symbol / gene name /gene id conversion function on the david website was used. The unique gene symbol/ name / id is include included gene_id.csv

  The env.yml included above, was the environment used. 

  ### To run code without additional biological data:

  -  The data can be downloaded directly form Kaggle at https://www.kaggle.com/c/msk-redefining-cancer-treatment/data
  - Clone notebook above.
  - Data needs to be in the same directory as the jupyter notebook. 


  ### To run code without additional biological data:

  -  The data can be downloaded directly form Kaggle at https://www.kaggle.com/c/msk-redefining-cancer-treatment/data
  - Clone notebook above.
  - Data needs to be in the same directory as the jupyter notebook. 

  - An additional library was used http://biopython.org/

  biopython was used and from Bio 'Entrez' was imported

  This was difficult to set up.

  The jupyter notebook should be able to run now top to bottom as is with running the additional biological code.

  The Capstone report is a pdf. The code to reproduce all results and images are in a jupyter notebook. Since the additional libraries were difficult to set up, all related code for the additional biological data is commented out so the jupyter notebook can be run easily from top to bottom. This will produce all other results. The pdf report will have information about the additional biological data. 

  Gene id was needed to search the ncbi website. The given data used gene name. Luckily  the biological website david.com has a conversion function. So I created a uniq_genes.csv  up loaded it to the david site and it covered the gene names to gene id and it was downloaded to my computer as gene_ids.csv. This file is also included in my submission. The Entrez web site were I did a search required my email address. This is in my code. If you chose to run the additional biology code you may need to change this to your email. I think it should work with my email.

  The david_full.csv, uniq_genes.csv and the input data file(from kaggle, the address is above) all need to be in the same directory as the jupyter notebook. 





