# DSBD-LendingClub-Project
Starting from 2015, the idea of Peer-to-Peer (P2P) lending emerged, which allows individuals (borrowers) to obtain loans directly from other individuals (investors) through platforms such as LendingClub, Prosper, and Upstart. This kind of "social lending" becomes an alternative financing approach, cutting out the financial institution as the middleman. P2P lending enables investors to acquire a higher return on investment compared to a bank deposit. However, credit risk, one of the biggest concerns for investors, emerges when they make informed investment decisions within the P2P lending procedure. In particular, a default due to failing to make the required payment within the agreed date for a borrower would induce a loss for an investor. 

In this project, we plan to develop a model that will predict whether a LendingClub-approved loan will end up being defaulted or not. The collected dataset includes loan grade, indicating the credit risk from the credit report and loan application. We plan to set the loan grade as the baseline and compare it with our model performance. In particular, we will draw a Precision-Recall Curve for the top 1%, 2%, 3%,..., 100% loans with default probability from high to low. We will also draw a Precision-Recall Curve for loan grade from A to G, and compare it with our models' Precision-Recall Curve. 

The domain of our project is as follows:
- Task (T) - Classification task that predicts defualted loan 
- Performance Measure (P) 
    - Precision: among all the actually defaulted loans, how many of them did we successfully identified
    - Recall: among all the loans that we predicted as default loans, how many of them actually defaulted
    - F-1 Score: weighted average for precision and recall
- Experience (E) - LendingClub database of loan records with loan status that we can use to label a loan as defaulted or not
<!-- machine-learned classification models (SVM, logistic regression, decision trees, random forests, XGBoost, etc.) -->

In sum, considering a classification task of identifying borrowers who are likely to make defaulted loans in LendingClub, we will train the LendingClub database of loan records without the pre-specified loan grades to perform the task and utilize precision, recall, and F-1 score as performance metrics to measure how well we complete the task.  
