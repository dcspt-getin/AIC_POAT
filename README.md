# AIC_POAT - Research Project Repository

This repository contains the code and documentation for the research project conducted at the University of Aveiro, Portugal. The project focuses on the evaluation of territorial impact from urban revitalization operations.

## Steps to properly run the Notebooks:
1) Clone the repository.
2) Some files are too big to be uploaded to Github. Download the 4 files available on the following link (ADD LINK) and follow the instructions below:
    - Place the file "BGRI21_CONT.gpkg" in the folder "../Approach_1/AIC_Regression/Data/BGRI21_CONT/"
    - Place the file "BGRI2011_PT_2.csv" in the folder "../Approach_1/AIC_Regression/Data/BGRI11/"
    - Place the file "BGRI11_CONT.shp" in the folder "../Approach_1/AIC_Regression/Data/BGRI11/CONTINENTE/"
    - Place the file "Cont_AAD_CAOP2022.shp" in the folder "../Approach_1/AIC_Regression/Data/CAOP_2022/"

## Project Structure

The repository encompasses 2 approaches to perform the evaluation of territorial impact from urban revitalizaion operations, divided in 2 folders:
- Approach 1 Folder (using Difference-in-Differences methodology)
- Approach 2 Folder (preferences evaluation for residence location)

### The Approach_1 Folder is organized as follows:

  AIC_Regression Folder containing:
  
    Notebooks Folder:
    - 01_ETL_AIC.ipynb
    - 02_Clustering_AIC.ipynb
    - 03_Modelling_AIC.ipynb
    - 04_Context_AIC.ipynb

    Data Folder:
    - All necessary files to run the notebooks
    
    Others Folder:
    - environment.yml and requirements.txt, with library information
    - Análise_Descritiva_POAT.html with the descriptive analysis of the variables used in the project
    
  Georref_Zones Folder containing:
    
    Notebooks Folder:
    - PreProcessing_Part0_GeoCode_PYCodPostal.ipynb
    - PreProcessing_Part1.ipynb
    - PreProcessing_Part2.ipynb
    - PreProcessing_Part3.ipynb
    - PreProcessing_Part4.ipynb
    
    Data Folder:
    - All necessary files to run the notebooks
    
    Others Folder:
    - environment.yml and requirements.txt, with library information

### The Approach_2 Folder is organized as follows:

    Notebooks Folder:
    - Prospect_ETL_v0.ipynb
    - Prospect_ETL_v1.ipynb
    
    Data_Pickles Folder:
     - All necessary pickles to run the notebooks
    
    Data_PROLIFIC Folder:
    - All necessary survey data to run the notebooks
      
    Others Folder:
    - environment.yml and requirements.txt, with library information
    
NOTE: CAOP and BGRI data can also be obtained at: https://www.dgterritorio.gov.pt/cartografia/cartografia-tematica/caop, https://mapas.ine.pt/download/index2021.phtml and               https://mapas.ine.pt/download/index2011.phtml (in case the link supplied on the "Steps to properly run the Notebooks" section doesn't work.
