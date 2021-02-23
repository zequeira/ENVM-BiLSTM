# ENVM-BiLSTM

LSTM-based Model for Noise Level Estimation.

The model was trainned on different spectral and chroma features extracted from the [DNLE dataset](https://github.com/zequeira/DNLE).


## Features:

- 20 MFCC
- 20 delta-delta
- 1 spectral centroid
- 12 chromagram
- 12 chroma energy normalized (CENS)


## Model Architecture

| Layer Type | Number of Layers | 
| ------------- |:-------------:| 
| LSTM  		| 3 |
| BiLSTM 		| 3 |
| LSTM  		| 3 |
| Regression	| 1 |


## Citing

If you find this model useful in an academic setting please consider citing:
(to be updated)


## Contact

Please get in touch for further information: (rafael.zequeira@tu-berlin.de)


