# Anti-spoofing for speaker verification

### ASVspoof 2019: Overview and Task Description

The ASVspoof 2019 challenge was aimed at developing countermeasures (CMs) to protect automatic speaker verification (ASV) systems against spoofing attacks. The challenge is part of a series of ASVspoof challenges (2015, 2017, 2019, and subsequent editions) focused on advancing the robustness of speaker verification systems in the face of increasingly sophisticated spoofing techniques.

### Dataset
The ASVSpoof2019 dataset can be downloaded from the following link:

https://datashare.is.ed.ac.uk/handle/10283/3336

### Implementation
#### Feature extraction technique 

Constant Q Cepstral Coefficients (CQCC) feature extraction technique is used. 
#### Neural network architecture

A deep residual neural network (Deep ResNet) is implemented.

#### Evaluation

Equal Error Rate (EER) is used for evaluation. EER is the error rate at which the False Acceptance Rate (FAR) and False Rejection Rate (FRR) are equal.


Walkthrough of the implementation is given in demo.ipynb