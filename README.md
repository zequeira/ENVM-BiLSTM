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


## Results

The [DNLE dataset](https://github.com/zequeira/DNLE) was split into 90% for training and 10% for testing. The model was trained with an *"adam"* optimizer, a learning rate of 0.0005, and a batch size of 675.
<br>
The model achieved an RMSE of 4.58 on average with a minimum of 0.5 and a maximum of 14.4 (scale of 30.6dBA to 81.3dBA), and a standard deviation of 2.72 on the test dataset.


## Citing

If you find this model useful in an academic setting please consider citing:
(to be updated)


## Contact

Please get in touch for further information: (rafael.zequeira@tu-berlin.de)


