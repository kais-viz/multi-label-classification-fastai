# <div align="center">Multi-label Classification using FastAi Library</div>

## Context
Applying Fastai library on apparel image dataset and creating a multi-label classification model based on what I learned from Jeremy Howard's [lesson 3 of the fastai course](https://course.fast.ai/videos/?lesson=3).

## Dataset
While searching the internet for a good dataset to apply the multi-label classification on, I stumbled upon pyimagesearch's  [multi-label classification with keras's](https://www.pyimagesearch.com/2018/05/07/multi-label-classification-with-keras/) article, and Adrian used a small simple dataset containing 3 clothing categories. But to expand on the dataset, I combined it with [trolukovich's dataset](https://www.kaggle.com/trolukovich/apparel-images-dataset) and my own by scraping Google and Bing using [cwerner's fastclass](https://github.com/cwerner/fastclass) package. Now it contains 8 different apparel categories in 9 different colours. It is published on Kaggle under the name [Apparel Dataset](https://www.kaggle.com/kaiska/apparel-dataset)

If you want to create your own image set, I highly recommend using Christian Warner's [fastclass package](https://github.com/cwerner/fastclass), he explains how to use it in a [short article](https://www.christianwerner.net/tech/Build-your-image-dataset-faster/).
Additionally, there is a [tutorial](https://www.pyimagesearch.com/2018/04/09/how-to-quickly-build-a-deep-learning-image-dataset/) on pyimagesearch which helps you build an image dataset by scraping bing, but it uses a more difficult approach and requires bing API which, if you are not a student, will require you to input your credit card information along side phone verification.

For this jupyter notebook, I will be applying the fastai library to classify the apparel and its colour within an image.