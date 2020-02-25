# audio-emotion-detection
SENG 474 (Data Mining) Group Project (with Muhammad Ali and Ryley Woodland): A Machine Learning Approach to Emotion Classification

We train two models to learn the underlying emotion present in audio recordings; we train a linear SVM model, and a Linear SVM model with an Radial Basis Function Kernel and PCA dimensionality reduction.

To create the dataset and extract the features yourself, first run create_dataset.py with the
Audio_Song_Actors_01-24 and Audio_Speech_Actors_01-24 directories (which can be downloaded at 
https://zenodo.org/record/1188976#.XKeTlZhKjD4) in the same directory as
create_dataset.py. This will create your train and test data in new directories labelled "Train"
and "Test" respectively. Then, run ./main.py to run the full pipeline (feature extraction plus training and testing of both models).

We write the features and labels of the train and test set into  4 files: X.txt, X_test.txt, y.txt and y_test.txt.

The libraries used for this project are: numpy 1.16.0, python_speech_features 0.6, sklearn 0.20.3, and librosa 0.6.3.


