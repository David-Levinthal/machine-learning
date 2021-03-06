# machine-learning
repository for notes and data from machine learning studies

Please feel free to point out errors or ask questions by submitting issues

The rapid rise in the successful use of machine learning (ML) algorithms raises the issue of what an optimal architecture for ML acceleration should look like. To help such an investigation, some discussion of the numerical operations of the dominant ML networks is required as a starting point. What follows will hopefully shed some light on this.
The two dominant ML network architectures, at the time of this writing, are convolutional neural networks (CNNS) and recurrent neural networks (RNNs). CNNs are currently dominantly used for 2-dimensional image recognition like surveillance, self-driving cars and drones and tagging which selfies have a cat. RNNs are dominantly used for sequential input (text, voice) recognition and manipulation respectively. As convolution is the basis for FFTs it is not surprising that CNNs are also useful in decomposing speech waveform patterns into phonemes, from which they can then be processed by RNNs into language and processed. These two techniques represent the dominant approaches in DNN applications.

https://github.com/David-Levinthal/machine-learning/blob/master/Introduction%20to%20machine%20learning%20algorithms.pdf

Useful applications for evaluating hardware performance and software support/performance for an assortment of frameworks

https://github.com/David-Levinthal/machine-learning/blob/master/public_csi_dnn_benchmarks.csv

A study of 4 layer seq2seq german to english translation on Tensorflow, MxNet and Pytorch. Both training and inference are studied. A novel use of problem size variation is used to distinguish GPU execution from platform related overhead.

https://github.com/David-Levinthal/machine-learning/blob/master/Evaluating%20RNN%20performance%20across%20HW%20platforms.pdf
