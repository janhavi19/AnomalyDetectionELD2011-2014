# AnomalyDetectionELD2011-2014

The importance of energy conservation and efficient energy utilization has significantly increased
in today’s world, leading to the need for monitoring systems and fault detection methods for these
system. Deep learning has evolved as a potent technique for fault diagnosis, allowing for accurate and
automated analysis of complicated data patterns and allowing for the rapid discovery and resolution of
defects, eventually minimizing downtime and enhancing system dependability. This thesis aims to analyze
Electrical Load data from UCI collected from 2011 to 2014 and study efficiency of available libraries and
algorithms for anomaly detection and give a comparative evaluation on this based on selected metrics.
The data was analyzed to obtain knowledge on to the patterns present in the consumption of electricity.
Preprocessing was done to handle the noise and changes in data due to daylight saving, along with this
the data was labeled to study supervised techniques based on assumptions. The thesis implements both
supervised and unsupervised algorithms for anomaly detection. There are five methods implemented
in total out of which two are open source libraries. The libraries have been reviewed based on the
implementation on the data. The methods implemented are Anomaly detection using LSTM Autoencoders
and DeepAnt library and anomaly classification using Torch time library, LSTM and LSTM Autoencoder.
It was observed from the results that the unsupervised methods work better at detecting anomalies
in comparison to supervised methods which might be due to the assumptions made in the labeling of
data. The model of the torch time library overfits the data due to the invariant nature of Inception time
module. LSTM Autoencoders performs better than the LSTMs in classification of anomalies. DeepAnt
and LSTM autoencoder perform similar to each other in detecting anomalies in data in unsupervised
manner.
