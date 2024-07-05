# BRAIN2SPEECH WITH DNN
Budapest University of Technology / Deep Learning Projectwork

# MEMBERS
Gulyás Gergely Zoltán - EH9JTC 

Imre Krisztián – GSE1U4

# BRAIN2SPEECH
The purpose of a brain-computer interface (BCI) is to provide a natural or near-natural channel of communication for people who cannot speak due to physical or neurological impairment. Speech is the primary and most essential means of human communication. However, many people have lost this ability through illness or ill health. The real-time synthesis of speech directly from measured neural activity (BRAIN2SPEECH) would enable natural speech and significantly improve quality of life, especially for severely communication-impaired individuals. Within the project, students study the BRAIN2SPEECH domain and then develop and train new types of neural network architectures. The suggested data is the 'Dataset of Speech Production in intracranial Electroencephalography' (SingleWordProductionDutch), available at https://osf.io/nrgx6/. The related github repository contains a linear regression model which should be replaced by deep neural networks. Basic task: train/valid/test set from single speaker. Advanced task: cross-speaker train and synthesis.

# RELATED WORKS/MATERIALS
https://github.com/neuralinterfacinglab/SingleWordProductionDutch

https://www.nature.com/articles/s41597-022-01542-9#Tab1

M. Verwoert, M. C. Ottenhoff, S. Goulis, A. J. Colon, L. Wagner, S. Tousseyn, J. P. van Dijk, P. L. Kubben, and C. Herff, “Dataset of Speech Production in intracranial Electroencephalography,” Scientific Data 2022 9:1, vol. 9, no. 1, pp. 1–9, jul 2022. [Online]. Available: https://www.nature.com/articles/s41597-022-01542-9

Bayram, I. An analytic wavelet transform with a flexible time-frequency covering. IEEE Transactions on Signal Processing 61, 1131–1142 (2012).

# DATA

![image](https://github.com/eva-vision/2BRAINS/assets/52841811/a63151c9-7b32-4f6e-a067-d1205f2aa78e)

# FUNCTIONS OF THE FILES

'docker' folder contains all the necessary files for Docker containerisation.
  'Dockerfile' 
  'docker-compose.yml'
  'final.py' contains the same solution as Final.ipynb
  'requirements.txt' contains the dependencies.

'Baseline.ipynb' contains a simple FC-DNN based regression.

'Baseline.ckpt' is a checkpoint for the baseline FC-DNN regression.

'Documentation' is a simple project presentation in pdf format.

'Final.ípynb' contains an FC-DNN based regression using 5 fold cross-validation.

'Final.ckpt' is a checkpoint for the final FC-DNN regression.

'MelFilterBank.py' makes Mel filtering on the audio data.

'extract_features.py' loads, extracts and prepares the raw data from the zipped data file available on https://osf.io/nrgx6/

'project_milestone_1.ipynb' CoLab notebook.

'reconstructWave.py' creates a .wav file from spectrogram data.

# HOW TO RUN IT

Run 'Final.ipynb' in CoLab or use the Docker files in your own environment.


