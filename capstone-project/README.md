# Machine Learning Engineer Nanodegree
## Capstone Project: Classifying German Traffic Sign Images
## ReadMe
__Ali Parsaei__<br>
December 19, 2017

Overview
---
In this project, we train and validate a model to classify traffic sign images using the German Traffic Sign Dataset. After the model is trained, we will then try out your model on images of German traffic signs in our test set as well as a few images from the web.

Project goals
---
The goals / steps of this project are the following:
* Load the data set
* Explore, summarize and visualize the data set
* Design, train and test a model architecture
* Use the model to make predictions on new images
* Analyze the softmax probabilities of the new images
* Summarize the results

Proposal
---
The __proposal.pdf__ is available in the project folder.

Software Requirements
---
This project is done using __Jupyter Ipython Notebook__ with __Python__. __Python 3.5.__ and the following Python
dependencies need to be installed to successfully compile the code:
- Ipython
- Jupyter
- Numpy
- Pandas
- SciPy
- Scikit-Learn
- OpenCV
- Matplotlib
- TensorFlow

Datasets
---
1. The dataset used for this project is the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset#Citation). Udacity has provided a pickled version of the images that are converted to (32, 32) color images for ease of use and smaller size. I used the same version of the dataset that can be downloaded from __[here](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/581faac4_traffic-signs-data/traffic-signs-data.zip)__.<br>

2. __'signnames.csv'__ is another file used in this project, which is available in the project folder.<br>

3. The random images that are downloaded from the web and are used in the testing step are included in __/test_images/__ folder.


**Sources**:
-  [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset#Citation).
- J. Stallkamp, M. Schlipsing, J. Salmen, and C. Igel. The German Traffic Sign Recognition Benchmark: A multi-class classification competition. In Proceedings of the IEEE International Joint Conference on Neural Networks, pages 1453–1460. 2011. 
- [Udaciy CarND Traffic Sign Classifier Project](https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project)
- __[Downloaded Dataset](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/581faac4_traffic-signs-data/traffic-signs-data.zip)__.

Final Note
---
The LeNet graph is stored in __/LeNet1/__ folder. Using this folder, you can __SKIP__ the __Training TensorFlow Session__ and use the model in the notebook (for testing and prediction).