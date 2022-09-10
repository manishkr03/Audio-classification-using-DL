# Audio-classification-using-DL

Dataset Link:

https://urbansounddataset.weebly.com/download-urbansound8k.html


Brief:


There are many techniques to classify images as we have different in-built neural networks under CNN, especially to deal with images. And it is easy to extract features from images because images already come in the form of numbers, as the formation of an image is a collection of pixels, and pixels are in the form of numbers. When we have data as text, we use the sequential encoder and decoder-based techniques to find features. But when the buzzing is about recognizing speech, it becomes difficult to compare it to text because it is based on frequency and time. So you need to extract proper pitch and frequency.

Audio classification employs in industries across different domains like voice lock features, music genre identification, Natural Language classification, Environment sound classification, and to capture and identify different types of sound. It is used in chatbots to provide chatbots with the next level of power.

Given an audio sample of some category with a certain duration in .wav extension and determine whether it contains target urban sounds. It lies under the supervised machine learning category, so we have a dataset as well as a target category.

Dataset Overview
The dataset we will use is called as Urban Sound 8k dataset. The dataset contains 8732 sound files of 10 different classes and is listed below. Our task is to extract different features from these files and classify the corresponding audio files into respective categories. You can download the dataset from the official website from here, and it is also available on Kaggle. The size of the dataset is a little bit large, so if it’s not possible to download, then you can create Kaggle Notebook and can practice it on Kaggle itself.

Air Conditioner
Car Horn
Children Playing
Dog Bark
Drilling Machine
Engine Idling
Gun Shot
Jackhammer
Siren
Street Music


Libraries:

Important and great library that supports audio and music analysis is Librosa. It provides building blocks that are required to construct an information retrieval model from music. Another great library we will use is for deep learning modeling purposes is TensorFlow.

pip install librosa

pip install tensorflow


