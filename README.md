# Predicting-Bioactivity-of-Compounds-using-Machine-Learning-Bioinformatics-Approach
## Disease Targeted in This Project
The project targets Acetylcholinesterase (AChE), an enzyme associated with neurological diseases, most notably Alzheimer's disease. Inhibitors of acetylcholinesterase are commonly studied for their potential therapeutic effects in Alzheimer's disease treatment.
for more information refer my blog portfolio[here](https://akshithasingareddy.wixsite.com/2022/post/predicting-bioactivity-of-compounds-using-machine-learning-a-comprehensive-bioinformatics-approach)
## Required Packages, Libraries, and Datasets
    ## General Python Libraries:
               numpy: For numerical operations.
               pandas: For data manipulation and analysis.
               scikit-learn: For machine learning model building and evaluation.
               matplotlib: For data visualization.
               seaborn: For enhanced data visualization.
               
    ## Bioinformatics-Specific Libraries:
               rdkit: For generating molecular fingerprints and working with chemical informatics data.
               chembl_webresource_client: For accessing ChEMBL database.
               
    ## Utility Libraries:
               urllib3: For handling HTTP requests.
               joblib: For saving and loading models.
               
## Installation Commands
               pip install numpy pandas scikit-learn matplotlib seaborn rdkit chembl_webresource_client urllib3 joblib

## Dataset
ChEMBL Database: Bioactivity data for acetylcholinesterase inhibitors can be retrieved from the ChEMBL database using the chembl_webresource_client library. Ensure you have access to the ChEMBL API or download the relevant dataset directly from their website.

## Project Outcome: What Did I Predict?
From this project, I successfully predicted the pIC50 values of compounds based on their molecular fingerprints. This prediction indicates how potent each compound is in inhibiting a specific target, allowing for the identification of highly effective compounds. The machine learning model developed in this project can be used to screen large libraries of compounds and prioritize those with the highest predicted bioactivity for further experimental validation. This contributes to a more efficient and cost-effective drug discovery process.


[reference](https://youtu.be/iZUH1qlgnys?si=VJOwZSiQ0_0PcFQK)
