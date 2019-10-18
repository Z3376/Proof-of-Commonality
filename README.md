# Proof-of-Commonality
A blockchain consensus hypothesis, based on anomaly detection using LSTM-GAN.

Common consensus protocols like Proof of Work, Proof of Stake etc. face problems (described in Doc) while scaling.
If we can select a subset of nodes based on certain criteria, only which will compete to create a block, this solves the scaling issue.

I propose the selection of nodes based on node behaviour score. 
Nodes with relatively common behaviour will have higher scores than nodes with abnormal behaviour. 
High scoring nodes will have high chance of getting selected.
This is called Proof of Commonality (PoC).
