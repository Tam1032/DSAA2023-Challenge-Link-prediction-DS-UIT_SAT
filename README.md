# DSAA2023 Challenge - Link prediction - DS@UIT_SAT team
This is our solution for the DSAA 2023 Competition: Link Prediction for Wikipedia articles. Our team, DS@UIT_SAT, currently ranks 7th in the leaderboard and achieved the final result of 0.99999 measured by F1-score metric on the private test set. <br />
## About
File DSAA2023_Preprocess explores the data and performs POS tagging. File DSAA2023_Model.ipynb runs the Machine Learning models and predict the results. The embedded files are too large, so we upload them to Google Drive together with the nodes.tsv file. Please click [here](https://drive.google.com/drive/folders/1PJi_n29WQRMFg4ZmmZ47YknPErrXojKX?usp=sharing) to view these files. <br />
## Reproduce the results
For reproducibility purposes, we created the file Full_pipeline.ipynb. This file performs the POS Tagging and run the Random Forest Classifier model - our model with the best prediction result. This file takes the train.csv, nodes.tsv and test.csv as input and outputs the submission file. Since the size of the nodes.tsv file is so large, we can't upload the file on Github, so please include this file on the folder before running Full_pipeline.ipynb file.
