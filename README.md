# AIC_POAT - Research Project Repository

This repository contains the code and documentation for the research project conducted at the University of Aveiro, Portugal. The project focuses on the evaluation of territorial impact from urban revitalization operations.

Please clone the repository in order to download the below structure of folders and files.

## Project Structure

The repository encompasses 2 approaches to perform the evaluation of territorial impact from urban revitalizaion operations, divided in 2 folders:
- Approach 1 Folder (using Difference-in-Differences methodology)
- Approach 2 Folder (preferences evaluation for residence location)

### The Approach_1 Folder is organized as follows:

  AIC_Regression Folder containing:
  
    Notebooks Folder:
    - 01_ETL_AIC.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/AIC_Regression/Notebooks/01_ETL_AIC.ipynb
    - 02_Clustering_AIC.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/AIC_Regression/Notebooks/02_Clustering_AIC.ipynb
    - 03_Modelling_AIC.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/AIC_Regression/Notebooks/03_Modelling_AIC.ipynb
    - 04_Context_AIC.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/AIC_Regression/Notebooks/04_Context_AIC.ipynb

    Data Folder:
    - All necessary files to run the notebooks.
    - Some files are too big to be uploaded to Github -> please download the 4 files available on the following link (ADD LINK) and follow the instructions below:
      - Place the file "BGRI21_CONT.gpkg" in the folder "../Approach_1/AIC_Regression/Data/BGRI21_CONT/"
      - Place the file "BGRI2011_PT_2.csv" in the folder "../Approach_1/AIC_Regression/Data/BGRI11/"
      - Place the file "BGRI11_CONT.shp" in the folder "../Approach_1/AIC_Regression/Data/BGRI11/CONTINENTE/"
      - Place the file "Cont_AAD_CAOP2022.shp" in the folder "../Approach_1/AIC_Regression/Data/CAOP_2022/"

    Others Folder:
    - environment.yml and requirements.txt, with library information
    - Análise_Descritiva_POAT.html with the descriptive analysis of the variables used in the project
    
  Georref_Zones Folder containing:
    
    Notebooks Folder:
    - PreProcessing_Part0_GeoCode_PYCodPostal.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/Georref.%20Zones/Notebooks/PreProcessing_Part0_GeoCode_PYCodPostal.ipynb
    - PreProcessing_Part1.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/Georref.%20Zones/Notebooks/PreProcessing_Part1.ipynb
    - PreProcessing_Part2.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/Georref.%20Zones/Notebooks/PreProcessing_Part2.ipynb
    - PreProcessing_Part3.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/Georref.%20Zones/Notebooks/PreProcessing_Part3.ipynb
    - PreProcessing_Part4.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/Georref.%20Zones/Notebooks/PreProcessing_Part4.ipynb
    
    Others Folder:
    - environment.yml and requirements.txt, with library information

NOTE: CAOP and BGRI data can be obtained at: https://www.dgterritorio.gov.pt/cartografia/cartografia-tematica/caop, https://mapas.ine.pt/download/index2021.phtml and               https://mapas.ine.pt/download/index2011.phtml.

### The Approach_2 Folder is organized as follows:

    Data_Pickles Folder:
     - All necessary pickles to run the notebooks. Please adapt the code accordingly (edit file path along the notebooks)
    
    Data_PROLIFIC Folder:
    - All necessary survey data to run the notebooks. Please adapt the code accordingly (edit file path along the notebooks)

    Notebooks Folder:
    - Prospect_ETL_v0.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%202/Notebooks/Prospect_ETL_v0.ipynb
    - Prospect_ETL_v1.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%202/Notebooks/Prospect_ETL_v1.ipynb
      
    Others Folder:
    - environment.yml and requirements.txt, with library information
