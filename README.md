# ECE 551
This repository explores my experiments done on the subject of sound based machine learning for UNM's ECE 551 - Projects course

The majority of the experiments have been set up to run in Google Colab. Please note that for Modules 6.1, 6.2, and 7, selecting a GPU workspace is critical for reasonable training times.

The project is broken up into modules that walk through the full process, with appropriate comments for each. The dataset is included, and explained within Module 1.

The modules can be run in order if desired, but all necessary files to run them in any order have been provided. The primary modules that demonstrate the learning models are:
* Module 3
* Module 4.2
* Module 6.1
* Module 6.2
* Module 7

The others are all support steps to generate the files that have been provided.

If you intend to run these on a local computer, Git LFS is necessary to download all of the pre-computed dataset files. You can run through the modules in order and generate them yourself without Git LFS.

In addition, 3 PyTorch weights files are provided that contain trained weights for the Cepstrum Coefficients CNN in Module 6 for two dataset types, along with the ResNet MFCC weights for Module 7. These are provided as examples of well trained networks, as the training can be somewhat unpredictable.

Reference material for the code developed is:

https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/ch03.html

https://www.github.com/pattichis/AIML/

https://docs.pytorch.org/vision/0.22/

https://scikit-learn.org/stable/api/index.html
