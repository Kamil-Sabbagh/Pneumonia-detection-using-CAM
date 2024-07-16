# Pneumonia-detection-using-CAM

First download the images folder and the labels from the following link:

```
https://www.kaggle.com/c/rsna-pneumonia-detection-challenge
```

Then we will use `stage_2_train_images` as the source of images.
The images in this folder will be devided into `Training`, `Validation`, and `Testing`.

The labels for this data can be found in the file `stage_2_train_labels.csv`.
The format of file will contain the name of the image, its label, and the values to drow the bounding box for postivate label cases.


finally we have `Pneumonia.ipynb` which does the pre-processing and create the dataloader, it also train or load model, and have the code for evalution based on the metric: **The percentage of CAM values inside the bounding from the whole picture.**

