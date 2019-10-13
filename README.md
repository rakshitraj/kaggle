# Machine Learning and Exploratory Data Analysis

​	Machine learning is informally defined as the ability of tasking computers to perform certain jobs without being explicitly programmed to do so. 

​	For example, a self-driving car, while being a case study in the application of machine learning  and AI is at no point during its production explicitly programmed to drive. To the unsuspecting autonomous vehicle, the road is just a snapshot of greyscale images and sensor data. The vehicle predicts the best response to the input data based on tons of similar data that was used to train the vehicle. Since this consisted mostly of pictures of the road and steering angles *(massive oversimplification)*, the vehicle is doing little more than predicting the same. The predictions are sent to the controls of the car which then runs as instructed.

​	From the above example, we may establish that Data plays a pivotal role in the implementation of Machine Learning. It is, in fact, the bread and butter of ML & AI applications. More data and better quality data help us make more accurate models and the information derived from their performance scientist to develop new algorithms that help us model our systems still closer to their real world counterparts.

However, this ideal set of data, as all ideal systems, does not exist in the real world. Actual data is prone to errors, missing data points, mislabelling and incorrect formatting usually served with a plethora of human and systematic errors made during collection. Sometimes there's just not enough data. 

Even there is a sufficient volume of data, it may be prone to presence of useless and *leaky* features that may cause our models to show erratic performance. Thus it is very important we determine what features to use and how to format the said features so that the computational cost of pre-processing and training models is reduced without compromising with model performance. This set of steps are referred to as **Exploratory Data Analysis** and **Pre-processing**

## Data, what ails thee?

There could be a lot that could go wrong in a dataset. From useless features to target leakage. Sometimes its not just the errors in data but the format of data itself, take non-numeric values for example. These values often referred to as categorical values are human-readable and can't be processed by a computer without pre-processing.

*In this repository, you will find the basics and examples of Data exploration and pre-processing of data. These examples cover the most of the basic cases and techniques.*

## Exploring the data

In this repository, we use a python library `seaborn` to visualize data. `Seaborn` is a handy python library, uses to plot beautiful and informative relations between data.

Check out the Data visualization notebooks here for examples and quickies.

- [Hello Seaborn!](https://github.com/rakshitraj/kaggle/blob/master/data_vis_1.ipynb)
- [Data Visuslization with Seaborn](https://github.com/rakshitraj/kaggle/blob/master/data_vis_2.ipynb)

## Pre-processing the data