# Kaggle Data Challenge
## Kernel methods in machine learning

The CSV files in the data challenge are not provided here in this repository. In summary they are

* Xtr.csv - the training images,
* Xte.csv - the test images,
* Ytr.csv - the image labels of the training images, in the same format as a submission file.

Xtr.csv contains a matrix of size 5000 x 3072. One row represents a color image of size 32 x 32 pixels. The first 1024 values represent pixel intensities on the red channel, then the next 1024 represent the green channel, and the last 1024 entries, the blue channel.  Note that images have been pre-processed, and do not appear as a natural image.

Similarly, Xte.csv contains 2000 test images. These are the ones you need to classify. The first row corresponds to image Id=1, then the last row corresponds to image Id=2000.

Ytr.csv contains a vector of labels corresponding to the training data, in the same format as a submission file.

**The goal is to classify the images in Xte.csv using a model trained on Xtr.csv and their associated labels Ytr.csv!**
