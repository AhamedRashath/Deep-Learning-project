DEEP LEARNING PROJECTS:

AUTO-MPG DATASET PROJECT:
It is a artificial neural network project in deep learning which I used artificial neural networks to predict the diabetes.I downloaded the data from kaggle website and that data contains lot of columns including the predictable feature 'class'.

About Dataset:
CONTEXT:
The data is technical spec of cars. The dataset is downloaded from UCI Machine Learning Repository

CONTENT:
1)Title: Auto-Mpg Data
2)Sources:
(a) Origin: This dataset was taken from the StatLib library which ismaintained at Carnegie Mellon University. The dataset was used in the 1983 American Statistical Association Exposition.
(b) Date: July 7, 1993
3)Past Usage:

a)See 2b (above)
b)Quinlan,R. (1993). Combining Instance-Based and Model-Based Learning.
In Proceedings on the Tenth International Conference of Machine
Learning, 236-243, University of Massachusetts, Amherst. Morgan
Kaufmann.
4)Relevant Information:

This dataset is a slightly modified version of the dataset provided in the StatLib library. In line with the use by Ross Quinlan (1993) in predicting the attribute "mpg", 8 of the original instances were removed
because they had unknown values for the "mpg" attribute. The originaldataset is available in the file "auto-mpg.data-original".

"The data concerns city-cycle fuel consumption in miles per gallon,to be predicted in terms of 3 multivalued discrete and 5 continuous attributes." (Quinlan, 1993).
5)Number of Instances: 398
6)Number of Attributes: 9 including the class attribute
7)Attribute Information:

a) mpg: continuous
b)cylinders: multi-valued discrete
c)displacement: continuous
d)horsepower: continuous
e)weight: continuous
f)acceleration: continuous
g)model year: multi-valued discrete
h)origin: multi-valued discrete
i)car name: string (unique for each instance).

Acknowledgements:
Dataset: UCI Machine Learning Repository
Data link : https://archive.ics.uci.edu/ml/datasets/auto+mpg

LIBRARIES USED:
1)Pandas
2)Seaborn
3)Matplotlib

METRICS USED:
1)Mean_absolute_error
2)Mean_squared_error.



RESTAURANT CUSTOMER REVIEWS PROJECT:
It is a recurrent neural network project in deep learning which I used recurrent neural networks to predict the restaurant customer reviews.I downloaded the data from kaggle website and that data contains columns including the predictable feature 'Liked'.

Context
Most of the Restaurants ask reviews to the customers and based on the reviews the restaurant can improve the customer satisfaction. So Reviews plays a vital role for the successful growth of the restaurant.

Content
The dataset consists of 1000 rows and 2 columns. Review Column consist of customer reviews and like column consist of 0 and 1. If the review is positive, 1 and if negative, 0.

LIBRARIES USED:
1)Pandas,
2)Seaborn,
3)Matplotlib.

TECHNIQUES USED:
1)Stopwords,
2)Wordcloud.

ALGORITHMS USED:
GaussianNB.
METRICS USED:
Classification Report,Confusion_matrix,Accuracy Score.



FASHION-MNIST IMAGE CLASSIFICATION PROJECT:
It is a Convolutional Neural Network project in deep learning which I used Convolutional Neural Network to predict all images.this dataset is available on jupiter notebook.Paper presents application of convolutional neural network for image classification problem. MNIST and FashionMNIST datasets used to test the performance of CNN model. Paperpresents five different architectures with varying convolutional layers, filter size and fully connected layers. Experiments conducted with varying hyper-parameters namely activation function,optimizer, learning rate, dropout rate and batch size. Results show that selection of activation function, optimizer and dropout rate has impact on accuracy of results. All architectures give accuracy more than 99% for MNIST dataset. Fashion-MNIST dataset is complex than MNIST. For Fashion-MNIST dataset architecture 3 gives better results. Review of obtained results and from literature shows that CNN is suitable for image classification for MNIST and Fashion-MNIST dataset.

Fashion-MNIST Image Classification using Deep Learning:
Fashion-MNIST consists of 60,000 training images and 10,000 test images. It is a MNIST-like fashion product database. The developers believe MNIST has been overused so they created this as a direct replacement for that dataset. Each image is in greyscale and associated with a label from 10 classes.
Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total.
Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255.


There are 10 different classes of images, as following:
0: T-shirt/top
1: Trouser
2: Pullover
3: Dress
4: Coat
5: Sandal
6: Shirt
7: Sneakers
8: Bag
9: Ankle boot
Image dimmensions are 28x28.

LIBRARIES USED:
MATPLOTLIB

METRICS USED:
Classification_Report






