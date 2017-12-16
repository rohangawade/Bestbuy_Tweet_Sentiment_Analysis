1. To run the ipynb files install Jupyter notebook
2. Go to the folder where code is present.
3. Copy BestBuy_Data.csv from additional_files folder to the code folder.
4. Run jupyter notebook.
5. Run LearningRationale.ipynb -> labelleddata.csv will be created.
6. Run Model_Using_Rationale.ipynb


The code folder contains
1. LearningRationale.ipynb - Give Label and Rationale to the tweets
2. Model_Using_Rationale.ipynb - Build Multinomial Naive Bayes, Logistic Regression and Linear Support Vector Machines with LwoR and LwR model.

The additional file folder contains 
1. BestBuy_Data.csv file which consist of raw tweets with manual given sentiments and rationale for 100 positive tweets and 100 negative tweets.
2. labelleddata.csv file is generated when we run the LearningRationale.ipynb file which uses Chi-Square statistics to give labels and rationales to other tweets.

