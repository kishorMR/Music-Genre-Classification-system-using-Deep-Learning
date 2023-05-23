# Music-Genre-Classification-system-using-Deep-Learning
A machine learning based academic mini project based on CNN.

This repository contains the code and resources for an audio genre classification project using Convolutional Neural Networks (CNNs).The aim of this project is to develop a model that can accurately classify audio files into different genres, such as rock, pop, jazz, hip-hop, and more.

# Introduction
Audio genre classification is a challenging task in the field of machine learning and signal processing. This project utilizes deep learning techniques, specifically CNNs, to automatically learn features from audio data and classify it into various music genres. By leveraging the power of deep learning, we can develop models capable of distinguishing between different genres with high accuracy.

**Dataset**
The GTZAN dataset is a widely used benchmark dataset for audio genre classification tasks. It consists of 1,000 audio clips of 30 seconds each, evenly distributed across 10 music genres: blues, classical, country, disco, hip-hop, jazz, metal, pop, reggae, and rock. Each genre contains 100 audio clips.The dataset provides a diverse collection of music genres, making it suitable for training and evaluating genre classification models.
To use the GTZAN dataset, you can download it from https://www.kaggle.com/datasets/carlthome/gtzan-genre-collection and make a better use of it 

**Architecture**
The model architecture used for audio genre classification is based on a CNN. The input to the model is a spectrogram representation of the audio, which is obtained by applying a Short-Time Fourier Transform (STFT) to the audio signal. The model consists of multiple convolutional layers followed by pooling layers to extract relevant features from the spectrogram. Finally, fully connected layers and a softmax activation are used for classification.

**Contributing**
Contributions to this project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue on the repository. You can also fork the repository, make changes, and submit a pull request if you'd like to contribute directly.

**License**
The code in this repository is licensed under the MIT License. Feel free to use and modify the code for your own purposes. However, please note that the dataset used for this project may have its own license, and you should refer to the dataset provider's terms and conditions for usage
