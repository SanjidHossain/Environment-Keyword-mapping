# Environmental Pollution Detection with Convolutional Neural Networks
## Introduction
Environmental pollution is a pressing global issue that requires urgent attention. Despite its widespread impact, effective measures to tackle pollution are still lacking. This study aims to develop an automated system for detecting pollution in the air, water, and land, with a focus on plastic-based pollution, dust, and smoke. By utilizing a convolutional neural network (CNN) with multiple layers of artificial neurons, we simulate the human learning process for visual pollutant categorization.

## Dataset and Preprocessing
The dataset used in this study is categorized into three levels of pollution: mild, average, and high. In order to compare results, the dataset was converted to grayscale, alongside the original RGB images. The annotation process was carried out to label the images accordingly. The dataset was split into training data (70%), validation data (20%), and test data (10%).<br/>
### You can find the data [Here](https://drive.google.com/drive/u/2/folders/1Qk9ycyt3saRUKjnUbD4rw2DqR_ZLv_OP)<br/>
![Image](https://github.com/SanjidHossain/Environment-Keyword-mapping/blob/main/Sample%20data.png)

## CNN Model and Training
The CNN model was employed for training and testing the pollution detection system. By leveraging deep learning techniques, the model learns to recognize visual pollutants from the provided images. The RGB images were used for training, and the grayscale images were used for comparison. The model's accuracy and loss were evaluated on the test data.

## Results
During the training phase, both RGB and grayscale images were evaluated in terms of training and validation loss. The RGB images showed superior performance in both validation and training loss, with a validation loss of 55% and a training loss of 56%. In contrast, the grayscale images exhibited a more significant discrepancy between validation and training loss, with a validation loss of 55% and a training loss of 92%.<br/>

During the testing phase, the performance of the model was evaluated on the test data. For RGB images, the test accuracy was found to be 75% with a loss of 56%. In comparison, the grayscale images achieved a test accuracy of 74% with a loss of 71%.

## Conclusion
Based on the evaluation results of the CNN model on the test data, it can be concluded that RGB images outperform grayscale images in terms of both accuracy and loss. The performance of the selected model and dataset demonstrated significantly better results for RGB images. Therefore, for the specific pollution detection system developed in this study, RGB images are recommended over grayscale images for improved performance.<br/>

The findings of this study contribute to the development of an automated pollution detection system, which has the potential to aid in mitigating environmental pollution. Further research could explore techniques such as data augmentation and fine-tuning the model architecture to enhance the performance of the pollution detection system.<br/>

## How to Use
To utilize the pollution detection system developed in this study, follow the steps below:<br/>

1. Obtain the RGB images representing the pollutants of interest.<br/>
2. Preprocess the images by converting them to grayscale.<br/>
3. Train the CNN model using the provided training data.<br/>
4. Evaluate the model's performance on the validation data and make necessary adjustments.<br/>
5. Finally, test the trained model on new images to detect and categorize pollutants automatically.<br/>
6. Please refer to the code implementation for detailed instructions and further information.<br/>

Contributors <br/>
[Mominul islam](https://github.com/Mominul-Islam-cmd)<br/>
[Md. Sanjid Hossain](https://github.com/SanjidHossain)<br/>
[Md. Sanzidul Islam]<br/>
[Md. Ismail Hossain]<br/>

 ### journal Paper will be added very soon <br/>

## Build from sources
1. clone the repo
```bash
git clone https://github.com/SanjidHossain/Environment-Keyword-mapping.git
```
2. intialize and activate virtual environment(for linux)
```bash
virtualenv --no-site-packages venv
source venv/bin/activate
```
3. install dependencies
```bash
pip install -r requirments.txt
