# 2022-NLP-PR
This is BIT NLP experiments calss final homework paper reproduction.
This repository contains data and code for ACL 2021 paper 

					COVID-Fact: Fact Extraction and Verification of Real-World Claims on COVID-19 Pandemic
					Arkadiy Saakyan, Tuhin Chakrabarty, and Smaranda Muresan.

Before coding i trying to figure out the purpose of this paper and method of experiment.
There is plenty of information on internet but due to indiscriminate provision of information, medical-information cannot be 
distinguished accurately. That's why we need tool of check the fact automatically.
The pipe line constructed by 
 1) consider real-world claim
 2) Retrieve relevant documents not bounded to a known document collection and which contain information to validate the claim.
 3) Select evidence sentences that can support of refute claim.
 4) Predict the claim veracity based on this evidence.



# COVID-Fact Dataset 
There is 4086 real-world claims with corresponding evidence documents and evidence sentences to support of refute the claim.
There are 1296 supported claims and 2790 automatically generated refuted claims.
And they semi-automatically construct the dataset.
1) select real-world true claims and trustworthy evidence documents.
2) automatic counter-claim generation
3) evidence sentence seleciton.
