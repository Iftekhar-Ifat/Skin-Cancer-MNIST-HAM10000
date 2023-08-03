# Extended Abstract

<small>IEEE CS BDC Summer Symposium 2023, IEEE Computer Society Bangladesh Chapter, May 2023</small>

## **Deep Learning-Based Mobile Application for Skin Cancer Detection: Enhancing Accuracy and Efficiency Using Diverse Datasets**

<b>Iftekhar Ahmed<sup>1</sup>, Biggo Bushon Routh<sup>2</sup>, \*Md. Saidur Rahman Kohinoor<sup>3</sup>, Shadman Sakib<sup>4</sup></b>

<sup>1,2,3</sup> CSE, Leading University, Sylhet, <sup>4</sup> ECE, University of North Carolina, USA

[iftekharifat007@gmail.com](mailto:iftekharifat007@gmail.com1)[<sup>1</sup>](mailto:iftekharifat007@gmail.com1), [routh.biggo123@gmail.com](mailto:routh.biggo123@gmail.com2)[<sup>2</sup>](mailto:routh.biggo123@gmail.com2), [kohinoor_cse@lus.ac.bd](mailto:kohinoor_cse@lus.ac.bd3)[<sup>3</sup>](mailto:kohinoor_cse@lus.ac.bd3), [sakibshadman15@gmail.com](mailto:sakibshadman15@gmail.com4)[<sup>4</sup>](mailto:sakibshadman15@gmail.com4)

<hr>

Cancer is a terrifying disease and one of the deadliest health issues worldwide, often proving to be incurable. Skin cancer, in particular, can cause serious health problems if left undetected and untreated. Early detection of any anomalies can lead to timely treatment and improve the chances of successful recovery. By developing a mobile application that can accurately and efficiently examine the skin for abnormalities, individuals can be alerted to seek medical attention as early as possible. By utilizing deep learning approaches, skin cancer can be classified with high levels of accuracy, allowing for early detection and effective treatment.

The present study aims to evaluate the performance of skin lesion classification using the HAM10000 dataset [1], which includes almost 10,000 dermatoscopic images of seven distinct types of skin lesions. In our continuing experiment, we assessed three neural networks—EfficientNet, MobileNet, and ResNet—both with and without adding additional data to produce outputs. We are investigating the use of segmentation utilizing the Unet architecture to increase the precision of our skin cancer detection model. The evaluated results for skin cancer classification we have obtained thus far are given below:

![Matrics](/data/matrics.png)

Figure 1: Comparison report on three different models using the HAM10000 dataset.

By choosing the top-performing model out of the three, MobileNet, we intend to build a mobile application for diagnosing skin cancer. We will merge datasets to get a larger and more diverse set of dermatoscopic images for model training for the application. This technique will improve our models' accuracy, our app's efficiency, and usability.

References:

1. Tschandl, P.; Rosendahl, C.; Kittler, H. The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions. Sci. Data 2018, 5, 180161.
