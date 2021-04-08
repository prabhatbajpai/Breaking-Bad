# Breaking-Bad
Aims to estimate proportion of cyber criminal activities over Bitcoin Blockchain Network.
Here we have collected blockchain bitcoin dataset from Blockchair and Merged it with Wallet_Explorer data. which provides us labels of particular transactions ,intially we have performed our analysis only over data of month November 2020,December 2020 and January 2020 , for ease of computation we have only selected four major classes of transaction which are Exchange,Mining Pools,Services and Gambling ,we can also add on some  other classes such as Darknet, Mixing Services etc.
To get dataset you can also use the same procedure.
In taining.ipynb we have tested the accuracy of various supervised learning approches and identify the best performing among them on the basis of Cross validation accuracy.
We have also provided sample code for Hyperparemeter tuning 
HPO algos used are  
>Grid Search 
>Random Search
>Hyperband
>Bayesian Optimization with Gaussian Processes (BO-GP)
>Genetic algorithm (GA)
