
# Sale Prediction Models-Data Mining

## Introduction
The sale prediction models implement various machine learning tools to classify the WholeSale data base and make prediction for future inventory
. The goal is forcus on performing cluster analyst on an inventory of a whole sale database (data was just a small sample) that data scientist can draw hypothesis from there.

### Technology
* Business Analyst
* Machine Learning
* Data Mining
* Data Visualization

### Algorithm & Methods
* Data Exploration: Explore min, max, mean, standard deviation, correlation, and else using describe function.
* Data Transformation: There is a lot of variation in the magnitude of the original data (org_data). To bring all the features to the same magnitude, standardize the features.
* Principal Component Analysis (PCA)
* Eigen Vector
* Hopskin Statistic
* 




## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Data
Please download data at [kaggle](https://www.kaggle.com/truchuynh87/wholesalecustomersdata) first.

### Prerequisites
What things you need to install the software and how to install them
- R Project:
- R IDE:

### Installing

A step by step series of examples that tell you how to get a development enviroment running

* [Install Anacoda Navigator](https://docs.anaconda.com/anaconda/navigator/install/#:~:text=Installing%20Navigator%20Navigator%20is%20automatically%20installed%20when%20you,install%20anaconda-navigator.%20To%20start%20Navigator,%20see%20Getting%20Started.) - If you haven't downloaded and installed Anacoda Navigator yet, here's how to get started.
* [Jupyter Notebook](https://jupyter.org/try) - Click here to go to the online free Jupiter Notebook.


## Running the tests

Explain how to run the automated tests for this system:
- There is no download IDE need, all you need is download all the src to your machine and run it.
- Using Jupiter Notebook
- Navigate to the file Kahman_Filter_Implementation.ipynb
- hit:

```
Ctrl + Enter
```
- The notebook will execute in Markdown form and include some data visualization to show the actual performance of kalmanfilter vs. lidar vs. round truth.

![alt](https://github.com/jackyhuynh/kalmanFilter-app/blob/main/src/picture/1.PNG)
## Deployment

Matrices class can be deploy and ready to work with any sensor, or moving robotic prediction. Idea for localization and/or self-driving car.
It turns out that using multiple sensors like radar and lidar at the same time, will give even better results. Using more than one type of sensor at once is called sensor fusion, which is used in Self-Driving Car applications.
Please refer to my notebook for better understanding.

## Built With

* [Jupyter Notebook](https://jupyter.org/try) 

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Truc Huynh** - *Initial work* - [TrucDev](https://github.com/jackyhuynh)

## Format
my README.md format was retrieved from
* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)
See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

