# eXamine

## Description

We are eXamine, a team of 5 students attending UC Berkeley, and our goal is to provide a software that can diagnose benign and malignant breast cancer based on ultrasound images. Our team consists of Amanda Quon, Anders Chiang, Gabriel Louis-Kayen, Jack Wang, Jeremy Yeung, and Rebecca Wang. When tasked with this project, we began by exploring many different ideas from stock market prediction to recipe recommendations and more because we have diverse interests within our group. Eventually, we decided to try to make a real impact on the world, and attempt to use image classification in order to detect and diagnose breast cancer using ultrasounds.

We chose to focus on ultrasounds, as opposed to X-rays or MRIs, for many reasons. Breast ultrasounds are useful when mammograms show an indistinct mass, does not show enough detail, when women should avoid radiation, and when mammograms are not accessible. Ultrasounds help the doctors determine whether the lump is a fluid-filled cyst or a solid tumor, the location and size of the lump, and the nature of a breast abnormality. However, ultrasound screening compromises the resolution of the images, posing challenges for doctors to interpret and patients who face a misdiagnosis rate of 50%. eXamine aims to decrease the rate of misdiagnosis, as well as provide quicker diagnosis times. 

At first, we struggled a lot with finding image data for our model. We asked peers, professionals, and scoured public resources to find image data of breast ultrasounds. In the end, we found around 1,000 breast ultrasound images that were pre classified into normal, benign cancer, and malignant cancer. 

Using convolutional neural networks, eXamine’s image classification software automates and expedites the ultrasound diagnosis process, predicting and classifying breast abnormalities with high confidence levels. In addition, ultrasounds do not expose patients to ionizing radiation, making it a safer procedure than techniques such as X-rays. Through training on public datasets, eXamine was able to achieve a validation accuracy of 78% with its model, significantly improving the misdiagnosis rate of 50% and optimizing the diagnosis process with machine learning. 

Our user interface is powered by Voila and ipywidgets, and sits on an easy-to-use website where users can upload images of ultrasound screening and quickly receive accurate classification and information. With internet connectivity, eXamine can process ultrasound images in seconds. Medical professionals can easily get access to eXamine without the geographic restriction. With such short processing time, radiologists and doctors no longer need to struggle with low resolution ultrasound screenings that require a long time to be processed. This results in negative consequences if a patient has a dangerous and undiagnosed condition.

eXamine hopes to help medical professionals and patients by optimizing breast abnormalities diagnosis process, thus reducing misdiagnosis and treatment delays in developing countries. 

We would love to further improve our model in the future by obtaining more image data as well as further fine-tuning our model. In articles published by Nature, we have seen some machine learning models classify images with accuracies of 88%-94%. Our goal is to eventually reach this accuracy level so that our product can be more useful in the real world. We would also like to further improve the UI, so that it is as easy and simple as possible for the user. 


## Running Final.ipynb

1. To run Final.ipynb to use the classifier on your local device, make sure you have the libraries within requirements.txt installed. To install a library, use the command pip install _library_name_ in your command line.

2. Then, navigate to the directory where you downloaded Final.ipynb. Download the png files and the pickle file. In the command line type in voila Final.ipynb and hit enter.

3. This should open up a new window in your browser and load up the UI. You can then proceed to upload the ultrasound images you like and the results should appear.

## To run eXamine Notebook 1.ipynb

1. To run eXamine Notebook 1.ipynb, navigate to the directory where you downloaded the notebook. It is recommended to run it on a cloud service such as Datalore, due to memory requirements.

2. The dataset also needs to be downloaded: https://scholar.cu.edu.eg/Dataset_BUSI.zip (for the first two models in Notebook). For the Convolutional Neural Network Model (final model) in the eXamine Notebook 1.ipynb, please download the dataset from here: https://drive.google.com/file/d/1lZtbE0saHqMB_wo2nd5dF9J5o3f1MxMB/view?usp=sharing

3. Then you should be able to run the notebook from start to finish.

