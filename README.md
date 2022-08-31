# BME590L Final Project: SMILES2vec with Attention for Classification and Regression in Pharmacology

## Abstract
Deep learning methods have been useful for de novo drug design and drug prediction. In recent years, many different types of networks have emerged to study 
the relationship between molecular structure and properties as well as improve network performance. In this project, we will compare and contrast the 
ability to predict chemical properties given SMILES between SMILES2vec, a recurrent neural network (RNN), a message passing neural network (MPNN) and our 
version of SMILES2vec with an attention mechanism implemented. The deep RNN, SMILES2vec, as well as the message passing (MP)-based attention network, MPAD, 
both consider the latent embedding from encoded SMILES to predict chemical properties with one key difference: the use of attention to consider the context 
of each atom within the molecule. We will analyze the models’ performances on predicting toxicity for compounds in the ClinTox dataset and skin reaction 
for compounds in the Skin Reaction dataset, and extrapolate the effectiveness of adding a custom attention layer into an existing RNN. 

This repo contains a Google Colab notebook where the work and findings are located. 
