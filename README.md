# Speech-Emotion-Recognition-Using-Deep-Learning-Models

Emotion recognition is becoming integral to
interaction technology with increasing human and
computer interactions. Improving Speech Emotion
Recognition (SER) from human speech can lead to
reliable outcomes in human-computer interaction.
Opportunistic prediction of mental health disorders has
become essential due to the rise in mental health
problems during the COVID-19 pandemic. A reliable
SER establishes a platform to act toward helping
humanity with mental health problems in real-time
modes of interaction. While deep learning strategies
have shown promise in the execution of SER compared
to machine learning techniques, an extended deeper
dive into using newer features is mostly limited to
audio-related features. To address this limitation, an
innovative approach is implemented using a
well-established deep feature extraction technique,
presenting the raw data through statistical features and
making the recognition customized to gender through a
gender feature.

The proposed architecture with the new
approach is SER-FusionNet, representing the fusion of
announced feature perceptions. SER-FusionNet consists
of two crucial deep learning modules: the 1-D
Convolutional Neural Network used in deep feature
extraction and the Multi-Layer Perceptron as a
classification module. A test accuracy of 88% is
achieved with SER-FusionNet on the augmented
Ravdess dataset. A robust and stiff evaluation avoids
any scope of overfitting and underfitting, for which
custom cross-validation is implemented with each fold
including unique actor representations and each fold
having an equal number of actors. With the Ravdess
dataset, a cross-validation accuracy of 0.45±0.05, is
achieved. To increase the diversity in the dataset in
terms of sentences spoken, voices involved, and the
number of audios recorded, a merged dataset called
SER Superset is created. The creation involves four
datasets: Ravdess , CREMA-D, SAVEE, and TESS. The
SER Superset generates a cross-validation accuracy of
0.43 ± 0.02, proving consistency over diverse data
