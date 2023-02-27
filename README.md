# correctorLSTM (cLSTM)
This repository includes corrector LSTM (cLSTM) with a running example on NAB. 
cLSTM is a machine learning algorithm with read and write priviledges. The algorithm operates in two modes: Learning and Correction. The learning mode corresponds to a standard LSTM. At the end of a given epoch, the correction mode is triggered. The latter has two stages: detection and correction.
The algorithm continue the learning after its corrections are done.

![alt text](https://github.com/YassineCodes/correctorLSTM/blob/main/results/cLSTM.png)

## Requirements
***
* Python: Version 3.10.8
* Pytorch: Version 1.7.1+cpu

## Usage
Run corrector_LSTM_main.ipynb.

It includes:
* fucntion detect(): Detection component
* class cLSTMModel

## Example:
Location: ./NAB-master/data\realTweets\Twitter_volume_IBM.csv

File Name: Twitter_volume_IBM.csv

### LSTM predictions
![alt text](https://github.com/YassineCodes/correctorLSTM/blob/main/results/LSTM_pred.png) 

LSTM RMSE --  1.3540998728929288

### corrector LSTM predictions
![alt text](https://github.com/YassineCodes/correctorLSTM/blob/main/results/cLSTM_pred.png) 

cLSTM RMSE --  0.43897822008515075

# Copyright and License
Yassine Baghoussi, Carlos Soares, João Mendes Moreira - Faculdade de Engenharia, Universidade do Porto - Portugal
