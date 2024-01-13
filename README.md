# Classifying Lung Tumors by Supervised Network Propagation

## Overview
In our project, we utilized a novel algorithm named Network-Based Supervised Stratification (NBS2), designed to identify and learn the specific subnetworks of mutations that underpin various lung cancer subtypes through a supervised learning approach. Utilizing a given molecular network annotated with reference tumor mutation profiles, where subtypes are already defined, NBS2 is calibrated. This calibration involves adjusting interaction feature weights to optimize the algorithm’s ability to accurately reflect these predefined subtypes. Training the classifier is conducted iteratively using gradient descent. When the algorithm reaches convergence, it produces three key outputs: the final feature weights, the transition matrix, and the propagated mutation profiles. These elements collectively form the basis of the classification model. Once the training phase is complete, the interaction weights are set, enabling NBS2 to effectively predict mutation profiles of validation set. Furthermore, by analyzing the interaction weights, NBS2 reveals key molecular pathways of lung cancer that are pivotal in the development of certain tumor subtypes, offering valuable insights into their underlying biological mechanisms.

## Contributors
- Wanzi Xiao
- Xueke Jin
- Zhiwen Yan
- Andy Yu

<p align="center">
  <img src="https://github.com/Wanzi-Xiao/Classifying-Lung-Tumors-by-Supervised-Network-Propagation/blob/main/figure/712poster.png" width="1200" height="800">
  </p>
