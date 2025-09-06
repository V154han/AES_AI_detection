# AES_AI_detection
AES and AI detection system code for my Master's dissertation

This is the readme file for the code used in creating the AES and AI-detection system. I've made this to highlight a few points about the code.



Please note that some of the cells can take a very long time to run, and I had to use the most powerful GPU available on Google Colab (A100) to gather the results (even then, certain cells took up to 3 hours). Within some of the cells, the hyperparameters used can be found, commented out, with certain global hyperparameters (such as epochs and patience) highlighted in the dissertation itself.  As well as this, you may notice large portions of the code commented out within the LSTM section. These were codes I used to fine-tune the models.

The general structure of the code is as follows:
- Regression-based AES codes
- Classification-based AES codes
- Regression stacking AES codes
- Classification stacking AES codes
- AI codes

The AI-detection dataset attached is NOT the full DAIGT V2 dataset. It is the filtered down version I used for my model. As a result, you can skip the first two cells in the 'AI Detection' section ('Importing data and performing EDA' and 'Creating an even split of the data'). However, make sure to import the dataset as a pandas dataframe beforehand. Kaggle links to the full dataset are also provided if you wish to view the full data. Also, please make sure to change the file paths as required as well as selecting the correct prompt (and its associated parameters).

