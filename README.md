# ExHistCNN
In this project, we address the problem of autonomous 3D exploration of an unknown indoor environment using a depth camera. We cast the problem as the estimation of the Next Best View (NBV) that maximises the coverage of the unknown area. We do this by re-formulating NBV estimation as a classification problem and we propose a novel learning-based metric that encodes both, the current 3D observation (a depth frame) and the history of the ongoing reconstruction. One of the major contributions of this work is about introducing a new representation for the 3D reconstruction history as an auxiliary utility map which is efficiently coupled with the current depth observation. With both pieces of information, we train a light-weight CNN, named ExHistCNN, that estimates the NBV as a set of directions towards which the depth sensor finds most unexplored areas. 

In this repo, we will share the code, dataset as well our pretrained models.