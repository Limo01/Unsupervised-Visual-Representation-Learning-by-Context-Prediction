# Unsupervised-Visual-Representation-Learning-by-Context-Prediction
In this work we study the problem of image representation learning without human annotation. By following the
principle of self-supervision we used several neural network
architectures previously trained to solve a context prediction task. This task, which no requires manual labeling,
consists in the use of the spatial context information through
the extraction of a central patch and one of the surrounding
patches from each image, and train a convolutional neural
network to predict the position of the second patch relative to the first. We tested two different grid sizes for the
patch extraction: 3x3 and 5x5. Furthermore, once this was
done, we used these pre-trained models to perform the image classification task. Finally, for each architecture used,
we compared the results of the pre-trained model against
the corresponding model trained from scratch. To do all
this, the datasets we worked on were Tiny ImageNet and
PascalVOC2012.

## Models
You can download all the models we used from this Google Drive [folder](https://drive.google.com/drive/folders/1-1YsnPnxzdBghWwBCyI7UpkI72dTvvjL?usp=sharing)
