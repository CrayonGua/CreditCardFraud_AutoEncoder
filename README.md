# CreditCardFraud_AutoEncoder
Artificial Intelligence course report, including the complete code contained in the project, as well as experimental images and results.

## Dataset
The dataset is Credit Card Fraud Detection Dataset from Kaggle.  
Due to file size limitations, creditcard.csv is not included in this repository.  
Please download the dataset from Kaggle and place creditcard.csv into the data/ folder before running the notebook.

## Files
- main.ipynb: complete experiment code
- figures/: generated figures
- results/: evaluation results

## Model
The model is a fully connected AutoEncoder.  
Input dimension: 29  
Encoder: 29 → 64 → 32 → 16  
Decoder: 16 → 32 → 64 → 29
