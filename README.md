# AIC_POAT - Research Project Repository

This repository contains the code and documentation for the research project conducted at the University of Aveiro, Portugal. The project focuses on the evaluation of territorial impact from urban revitalizaion operations.

## Project Structure

The repository encompasses 2 approaches to perform the evaluation of territorial impact from urban revitalizaion operations, divided in 2 folders:
- Approach 1 Folder (using Difference-in-Differences methodology)
- Approach 2 Folder (preferences evaluation for residence location)

### The Approach 1 Folder is organized as follows:

  AIC_Regression Folder containing:
  
    Notebooks Folder:
    - 01_ETL_AIC.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/AIC_Regression/Notebooks/01_ETL_AIC.ipynb
    - 02_Clustering_AIC.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/AIC_Regression/Notebooks/02_Clustering_AIC.ipynb
    - 03_Modelling_AIC.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/AIC_Regression/Notebooks/03_Modelling_AIC.ipynb
    - 04_Context_AIC.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/AIC_Regression/Notebooks/04_Context_AIC.ipynb

    Data Folder:
    - All necessary files to run the notebooks. Please adapt the code accordingly (edit file path along the notebooks)

    Others Folder:
    - AIC_Requirements.txt, with library information
    - HTML file with the descriptive analysis of the variables used in the project
    
  Georref. Zones Folder containing:
    
    Notebooks Folder:
    - PreProcessing_Part0_GeoCode_PYCodPostal.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/Georref.%20Zones/Notebooks/PreProcessing_Part0_GeoCode_PYCodPostal.ipynb
    - PreProcessing_Part1.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/Georref.%20Zones/Notebooks/PreProcessing_Part1.ipynb
    - PreProcessing_Part2.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/Georref.%20Zones/Notebooks/PreProcessing_Part2.ipynb
    - PreProcessing_Part3.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/Georref.%20Zones/Notebooks/PreProcessing_Part3.ipynb
    - PreProcessing_Part4.ipynb - https://github.com/dcspt-getin/AIC_POAT/blob/main/Approach%201/Georref.%20Zones/Notebooks/PreProcessing_Part4.ipynb
    


NOTE: CAOP and BGRI data can be obtained at: https://www.dgterritorio.gov.pt/cartografia/cartografia-tematica/caop, https://mapas.ine.pt/download/index2021.phtml and               https://mapas.ine.pt/download/index2011.phtml (edit file path along the notebooks)

### The Approach 2 Folder is organized as follows:

    Data - Pickles Folder:
    - All necessary pickles to run the notebooks. Please adapt the code accordingly (edit file path along the notebooks)
    
    Data - PROLIFIC Folder:
    - All necessary survey data to run the notebooks. Please adapt the code accordingly (edit file path along the notebooks)

    Notebooks Folder:
      - Prospect_ETL_v0.ipynb
      - Prospect_ETL_v1.ipynb
