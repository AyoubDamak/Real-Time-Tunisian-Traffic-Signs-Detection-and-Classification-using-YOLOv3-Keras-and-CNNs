# Real-Time-Tunisian-Traffic-Signs-Detection-and-Classification-using-YOLOv3-Keras-and-CNNs
The code of this project is divided into three Notebooks, each of them fulfills a specific task.
Some of these Notebooks require additional files in order to run with no errors.

## Application.ipynb:
This notebook contains the main code for executing the application. Three mode of execution are available:

Mode 1: Real-Time with no video saving.

Mode 2: Real-Time with video saving.

Mode 3: Video playback (Usage on a recorded video) with video saving.

## Classification_Model_Training.ipynb:
This notebook contains the code for the Classification model initialization and training as well as a few visual representations including a plot of the training phase and a confusion matrix of the model prediction.

## Classification_Data_Processing.ipynb:
This notebook contains the code for Cleaning, Adapting and Preprocessing the raw data in order to prepare it as input for the Classification model.

## GPU Acceleration:
GPU acceleration with Cuda Cores is required for both Tensorflow and OpenCV. The output of the first cell of the Application Notebook should indicate if these modules are properly installed and configured.
Useful links to install Cuda and configure GPU acceleration:

OpenCV: https://www.youtube.com/watch?v=YsmhKar8oOc

Tensorflow: https://www.youtube.com/watch?v=IubEtS2JAiY&t=6s
