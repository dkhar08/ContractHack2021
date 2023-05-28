# ContractHack2021
MCB hackathon 2021. 10th place private leaderboard. 3rd place judges' decision.

It was my first hackathon. The solution has some ambiguous moments, like one-hot encoding of categorical features for lgbm(I just simply switched between different models with the same features and found that lgbm worked faster and better than the other) or weak hyperparameters search. And I have corrected them in my future works. 

The goal of the hackathon was to predict probability the probability that the company would be a violator of the contract. The same companies occur many times in the dataset and with time I found that common contract load was the key to the victory. You just needed to calculate how many contracts the firm had. And firms that get too many contracts most likely wouldn't fulfil them.
