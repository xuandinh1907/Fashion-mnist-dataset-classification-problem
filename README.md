# Overview
Fashion-MNIST is a dataset of Zalando's article images consisting of a training set of 60,000 examples and a test set of 10,000 examples.Each example is a 28 x 28 grayscale image,associated with a label from 10 classes.Zalando intends Fashion-MNIST so serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

The original MNIST dataset contains a lot of handwritten digits.Members of the AI/ML/Data Science community love this dataset and use it as a benchmark to validate their algorithms.In fact,MNIST is often the first dataset researchers try.*"If it doesn't work on MNIST,it won't work at all"*,they said.*"Well,if it does work on MNIST,it may still fail on others"*

Zalando seeks to replace the original MNIST dataset

# Content
Each image is 28 pixels in height and 28 pixels in width,for a total of 784 pixels in total.Each pixel has a single pixel-value associated with it,indicating the lightness or darkness of that pixel,with higher numbers meaning darker.This pixel-value is an integer between 0 and 255.The traning and test data sets have 785 columns.The first column consists of the class labels and represents the article of clothing.The rest of the columns contain the pixel-values of the associated image.
- To locate a pixel on the image,suppose that we have decomposed x as x = i * 28 +j,where i and j are integers between 0 and 27. The pixel is located on row i and column j of a 28 x 28 matrix
- For exmaple,pixel31 indicates the pixel that is in the fourth column from the left,and the second row from the top

# Labels
Each training and test examples is assigned to one of the following labels:
- 0 T-shirt/top
- 1 Trouser
- 2 Pullover
- 3 Dress
- 4 Coat
- 5 Sandal
- 6 Shirt
- 7 Sneaker
- 8 Bag
- 9 Ankle boot

# Acknowledgements
- Original dataset was downloaded from [github.com/zalandoresearch/fashion-mnist](https://github.com/zalandoresearch/fashion-mnist)
- Dataset was converted to CSV with this script[pjreddie.com/projects/mnist-in-csv/](https://pjreddie.com/projects/mnist-in-csv/)

# License
The MIT License (MIT) Copyright © [2017] Zalando SE,[jobs.zalando.com](https://jobs.zalando.com)

Permission is hereby granted,free of charge to any person obtaining a copy of this software