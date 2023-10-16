# Introduction
This is LKAU23 Team effort on the Quran QA 2023 Task A Passage Retrieval. 

# Please follow the instructions

For Task A, there are three files that are submitted for the competition. Two are from individual models and the last one is an ensemble of two models.

The models are:
1- ArabicBERT
2- CL-AraBERT

# For folder 'Step 1 Individual Models':
The notebooks are for training the models and retrieve the relevant passages for top 20. Store them into two files for each model for ensemble method. Then, we extract the top 10 answers and store them into two separate files as a final test files.
So, the order is:
- ArabicBERT.ipynb
- CL-AraBERT.ipynb
- 10_answers_for_each_model.ipynb

# For folder 'Step 2 Ensemble':
We take the two files that have top 20 answers, then ensemble them and later delete the duplicates and cap it at 10 answers. Later, we save the file.

# Citation
Please use this if needed. Thank you
