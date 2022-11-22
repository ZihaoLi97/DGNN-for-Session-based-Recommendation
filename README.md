# DGNN-for-Session-based-Recommendation

This is a Pytorch implementation for our WSDM 2023 paper:

> Zihao Li, Xianzhi Wang, Chao Yang, Lina Yao, Julian McAuley, Guandong Xu. 2023. Exploiting Explicit and Implicit Item relationships for Session-based Recommendation. In Proceedings of the Sixteenth ACM International Conference on Web Search and Data Mining (WSDM '23).

Contributors: Zihao Li.

## Overview

We propose to decouple the modeling of explicit dependencies and implicit correlations among items for session-based recommendation.
To this end, we present a dual graph neural network (DGNN), where a GNN with a single gate (SG-GNN) captures the explicit dependencies as reflected by the ordering of items in sessions, and an adaptive GNN (A-GNN) learns implicit correlations between any two items adaptively with a self-learning strategy.

![framework](framework.png)

## Acknowledgement





