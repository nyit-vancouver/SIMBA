# SIMBA: An Efficient Simulator for Blockchain Applications
Predicting the performance of a blockchain application during the design phase is difficult and evaluation after it is built could be expensive. The ability to simulate a blockchain network during the design stage in order to evaluate it is therefore a necessity. In this paper, we present a simulator for blockchain applications, called SIMBA (SIMulator for Blockchain Applications). SIMBA extends an existing simulator (BlockSim) by adding the Merkle tree feature to blockchain nodes to improve efficiency and allowing more realistic evaluations not possible with the base tool to be performed. Results of our experiments show that the inclusion of Merkle trees has a high impact of up to 30 times reduction in the verification time of block transactions without an impact on block propagation delay. Since block verification is a critical part of the computational load of nodes on the network, this performance improvement significantly affects the overall performance of each node and consequently the entire network.

# Simulation results
You can find more information on the study that we carried out [here](https://docs.google.com/spreadsheets/d/1XL2-UALnJVKZfALbkNZkpuciBYoyD4ZAxq1csKob3-Q/edit?usp=sharing).

# Paper
S. M. Fattahi, A. Makanju, A. Milani Fard, ["SIMBA: An Efficient Simulator for Blockchain Applications”](people.ece.ubc.ca/aminmf/DSN2020.pdf), The 50th IEEE/IFIP International Conference on Dependable Systems and Networks (DSN), 2020.


# Citation
```
@inproceedings{fattahi2020simba,
  title={SIMBA: An efficient simulator for blockchain applications},
  author={Fattahi, Seyed Mehdi and Makanju, Adetokunbo and Milani Fard, Amin},
  booktitle={50th Annual IEEE-IFIP International Conference on Dependable Systems and Networks-Supplemental Volume (DSN-S)},
  pages={51--52},
  year={2020},
  organization={IEEE}
}```

# Clarification
Pleasse note that our simulator has no connection with the company SIMBA Chain Inc. that focuses on creating blockchain applications, where SIMBA (Simple Blockchain Applications) is a platform to deploy a blockchain network.
