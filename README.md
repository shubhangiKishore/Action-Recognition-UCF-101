# Action-Recognition-UCF-101
Action Recognition from Video DataSet using Recurrent Neural Networks (LSTM) using Pytorch


Action recognition using Recurrent Neural Network (RNN), (Long-Short Term Memory) LSTM in particular on UCF101, which consists of 101 different actions/classes and for each action, there are 145 samples. Each sample is supposed to be a short video, but  25 frames are sampled from each videos to reduce the amount of data. Consequently, a training sample is an image tuple that forms a 3D volume with one dimension encoding temporal correlation between frames and a label indicating what action it is.  To tackle this problem, we aim to build a neural network that can not only capture spatial information of each frame but also temporal information between frames. This is part of the Computer Vison Course by Dr. Dimitris Samaras at Stony Brook University. 
