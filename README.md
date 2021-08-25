# Negative Interactions for Improved Collaborative Filtering: 
# Don’t go Deeper, go Higher

This notebook provides an implementation in Python 3 of the algorithm outlined in the paper 
"Negative Interactions for Improved Collaborative Filtering: Don’t go Deeper, go Higher" published 
at the 15th ACM Conference on Recommender Systems(RecSys 2021), Amsterdam, Netherlands.

The results of Table 1 in this paper can be reproduced in the following three steps:
- Step 1: Pre-processing the data (as in this publicly available [code](https://github.com/dawenl/vae_cf))
- Step 2: Loading the pre-processed data, and defining the evaluation-functions (as in this publicly available [code](https://github.com/dawenl/vae_cf))
- Step 3: Learning and Evaluating the higher-order model in this paper.

We use the same code for pre-processing the data and evaluating the model as was made publicly available in this [code](https://github.com/dawenl/vae_cf)), which accompanies the paper "[Variational autoencoders for collaborative filtering](https://arxiv.org/abs/1802.05814)" by Dawen Liang et al. at The Web Conference 2018. 
While their code for the Movielens-20M data-set was made publicly available, the code for pre-processing the other two data-sets can easily be obtained by modifying their code as described in their paper.
