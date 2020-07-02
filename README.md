# Reproduction of Query Autocompletion of rare prefixes

For this project we tried to reproduce the paper "Query Auto-Completion for Rare Prefixes" out 2015 by Bhaskar Mitra and Nick Craswell from Microsoft. 

#### We have reproduced parts and also partly applied other methods. 

In the notebooks-folder, one can find six notebooks in the other it has to be run:
* Create synthetic query keys based on samples of the historical logs (AOL query logs)
* Generate features based on the original and synthetic keys
* Split the dataset into three parts (validation, test and training)
* Convert the files into LambdaMART files and run lambdaMART to calculate the MRR & NDCG
* Calculate the Most popular completions via Mean Reciprocal Ranking
* Importance of the features generated at part 2.

We have used the AOL dataset for our synthetic queries & history log:
http://www.cim.mcgill.ca/~dudek/206/Logs/AOL-user-ct-collection/
