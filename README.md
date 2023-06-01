# DO REPLICATION MODELS REPLICATE? 
This repository was used for a replication attempt of the paper [Estimating the deep replicability of scientific findings using human and artificial intelligence](https://www.pnas.org/doi/10.1073/pnas.1909046117) by Yang et al.. This was done as part of the course Applied Cognitive Science at the Bachelor program in Cognitive Science at Aarhus University. The repository contains:

- A database of abstracts of linguistics papers that we subjectively hand coded with replication outcomes
- A python script for converting the abstracts into TF-IDF weights, then using these to reweight a word2vec model trained by Yang et al, and use this reweighted model to train a classifier.
- A r-script for visuazaling model performance based on simulating 1000 random model fits
- Various visuazilations of model outcomes and the diagrams of how the data was processed
- The resulting report

## How to use this repo
To retrain the models, you will need to download the [word2vec model](https://osf.io/w5h8j) made by the same authors for a different paper [A discipline-wide investigation of the replicability of Psychology papers over the past two decades](https://www.pnas.org/doi/10.1073/pnas.2208863120). and store it in the data folder. We hope that this work can be of use to anyone. 

### Data
The data base contained in the *data folder* and used as training material for the model is dependent on the database assembled and published by Kristina Kobrock and Timo B. Roettger. All credit for systematically identifying replication studies within the experimental linguistics literature goes to their original work.

Reference: Kobrock, K., & Roettger, T. B. (2023). Assessing the replication landscape in experimental linguistics. Glossa Psycholinguistics, 2(1). https://doi.org/10.5070/G6011135![image](https://github.com/christianstenbro/replica/assets/83128748/84095f7a-441f-4859-b970-bffc64a22aa3)


*** 

Emil Frej and Christian Stenbro
