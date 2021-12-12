# Music Genre Classification

# Given files in the Software_Project.zip:
1. FinalProject.ipynb
This is the jupyter notebook containing all of the src code required to re-compile and produce my results.
2. Data
This directory contains a csv file and a folder that contains extracted features and the raw audio files (1000).

# Tech Specs
Anaconda or any application that can run jupyter notebooks (eg. Google Colab (preferred) or JupyterLab)
numnpy, pandas, scipy, sys, os, tensorflow (latest version), keras, pickle, librosa, sklearn and matplotlib 

# Steps to compile the file
1. Unzip the folder 
2. Make sure the Data dir and the FinalProject.ipynb are in the same directory
   ** If not in the same dir, then, you have to set the file path accordingly in the notebook wherever required **
3. Open the FinalProject.ipynb 
4. Run each and every cell in the ascending order without changing any src code 
5. You should see the output of each cell as you run it, if it has any.
6. At then end, when we test the model, you may change the index of the X_test, y_test
   to test on different values, but the index must be < 3497 and the indices should be the same 
   that is X_test[ i ], y_test[ i ]
