# MSVS Dataset 
The MSVS Dataset is a dataset of infrared visible video sequences for nighttime road scenes.The MSVS dataset is organized from the [FLIR](https://www.flir.com/oem/adas/adas-dataset-form/) dataset and contains the challenges of both very low light and glare, and is intended to facilitate research in the fields of computer vision and image processing.

# Dataset Description
The MSVS dataset contains six groups of video sequences, each containing infrared video sequences, visible video sequences, and aligned infrared video sequences, and each type of video sequence (visible video sequences, infrared video sequences, or aligned infrared video sequences) contains 2151 images. The features of the infrared and visible video sequences include:
 + Data format: JPG
 + Image resolution:
   + Infrared image: (640, 512)
   + Visible Image: (1224, 1024)
     
In order to better metricize the video registration and fusion task, we manually aligned image pairs with the same frame sequence number under a uniform video sequence (aligning from infrared images to visible images). We set the resolution of the aligned IR images to (640, 480) size. Aligned infrared video sequences are characterized as follows:
 + Data format: JPG
 + Image resolution: (640, 480)
   
# Dataset Organization 
The MSVS dataset is organized in the following format:

Dataset:
  + vid:
    + vi:
    + ir
    + ir_label
  +  ...

vid: Indicates the number of the video sequence.
vi: The folder where the visible video sequences are stored.
ir: The folder where the infrared video sequences are stored.
ir_label: The folder where the aligned infrared video sequences are stored.

# Download
We have posted at Google Drive.
+ [Google Drive](https://drive.google.com/drive/folders/1wJDRmsSmdtfOV5CsfhyfXFsR__nYilcl?usp=drive_link)

# Result
The effect of our algorithm's registration and fusion in this dataset will be published in a subsequent collation.

