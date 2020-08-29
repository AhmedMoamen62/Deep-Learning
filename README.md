## Deep Learning
* This repository has all solutions, assignments, files and slides for [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) at Coursera

* [Drive Link](https://drive.google.com/drive/folders/18cWuPh4jSS8f59mH9Py9q1B0kfBc_1Qk?usp=sharing) for all big files (slides, yolo.h5, ResNet50.h5, imagenet-vgg-verydeep-19.mat, glove.6B.50d.txt, X.npy, X_dev.npy)

## How to download coursera jupyter notebook and all reference files ?

1. Open a online jupyter notebook, and then click `File > Open ...`
2. Launch new terminal instance: `New > Terminal`
3. tarball the folder:
```shell
tar czvhf coursera.tar.gz *
```
3. a. split it (usually this file might be too large for your instance to allow download)
```shell
split -b 100M -d coursera.tar.gz coursera.
```
4. Go to view in 2.
5. Download the file(s) by selecting it (square) then clicking on `Download`.

6. if you split the file, join them:
```shell
cat coursera.* > coursera.tar.gz
```
7. Extract files:
```shell
tar xzvf coursera.tar.gz
```