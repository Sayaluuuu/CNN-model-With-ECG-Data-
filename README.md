Project Overview:

This project focuses on the classification of Electrocardiogram (ECG) signals using deep learning techniques
It utilizes ECG data in PTB Training (.mat and .hea files), which are extracted, preprocessed, and converted into structured signal-label datasets.
The objective is to build and compare models that can automatically identify heart conditions from raw ECG waveforms.

Model Used:

 CNN (Convolutional Neural Network): Captures spatial patterns from 1D ECG signals.

 Workflow Summary :
1.
Data Loading
. Extract .mat and .hea files using the wfdb library.
. Signals are flattened or zero-padded to a fixed length (e.g., 5000 samples).
. Diagnosis labels are extracted from header comments.

2. Preprocessing:
   . Signals reshaped to 3D input format (samples, timesteps, features).
   . Labels are one-hot encoded for multi-class classification.


 
