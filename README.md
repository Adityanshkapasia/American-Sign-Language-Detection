## About The Project
The project focuses on the classification of American Sign Language (ASL) characters using a 4-layer Convolutional Neural Network (CNN). This endeavor aims to identify and analyze various ASL signs represented through hand gestures in images. The CNN model is designed to process these images and classify them into corresponding ASL characters. This approach allows for the exploration of effective techniques in sign language recognition, leveraging deep learning to enhance the understanding and interpretation of ASL. The project integrates data preprocessing, model training, and evaluation to establish a comprehensive solution for ASL character classification.


## Dataset
Data_train.npy and labels_train.npy, the datasets for this project, contain images of various ASL signs. ASL signs are meticulously labeled on each image. In order to assess the CNN model's performance, the dataset is divided into training and testing sets. As a result of this structured approach, a comprehensive evaluation is ensured, highlighting the model's ability to correctly classify ASL signs. As shown in the screenshot provided, the results of this evaluation demonstrate the model's efficacy.

## How to load Files 
Load training data and labels from numpy files, 
In training to load data 
for dataset replace by your dataset file name in our case "data_train.npy", 
for lables replace by your lables file name in our case "lable_train.npy"

## Extra Credit Load Files
In this ipynb file, replace by your dataset file name

## Results
The model successfully supports accuracy, demonstrating the ability to correctly identify ASL characters. You can find detailed performance information in the testing section of this repository.

## Dependencies
These are all libraries, packages, and other dependencies that need to be installed to run the project.
<ol>
  <li>Conv2D</li>
  <li>MaxPooling2D</li>
  <li>Flatten</li>
  <li>Dense</li>
  <li>Dropout</li>
  <li>BatchNormalization</li>
  <li>Adam</li>
  <li>TensorFlow 2.7.0 (HiperGator Kernel) </li>
  <li>ImageDataGenerator</li>
  <li>L2</li>
  <li>Skimage</li>
  <li>Numpy</li>
</ol>

<br />

## Usage
Instructions for installing and operating the model are as follows:
<ol>
  <li>Clone the repository.</li>
  <li>Install the required dependencies.</li>
  <li>Prepare training manuals to demonstrate the model, name "train.ipynb".</li>
  <li>Evaluate the model using a test called "test.ipynb".</li>
  <li>The trained model is saved in the file named as"final_model.h5". This file will be generated as we run the "train.ipynb"</li>
</ol>

<br />


## Contributing

You are encouraged to contribute to the ASL Character Classification project. If you have ideas for enhancement, kindly adhere to these steps:

1. Begin by forking the project on GitHub, creating your own copy.
2. Next, establish a feature branch using the command: `git checkout -b newFeature/WriteYourFeature`.
3. Commit your modifications with meaningful messages like: `git commit -m 'Add some WriteyourFeature'`.
4. Push these changes to your branch to upload them to your fork.
5. Lastly, initiate a Pull Request to propose your changes for potential inclusion into the main project.

<br />

## Liscense
This project is distributed under the MIT License. Refer to `License.txt` for further details.

<br />
