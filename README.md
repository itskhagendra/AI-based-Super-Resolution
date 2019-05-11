# AI Based Super Resolution

The Super Resolute (SR) model enhances the
quality of a low-resolution image to a high
resolution. The quality of the output image will
be significantly improved and contain more
details. The existing system uses deep neural
network to enhance the image quality by
applying the little filters many times in deep
network which help get more contextual
information over the low resolute image. The
proposed model uses CNN (Convolutional
Neural Network) to extract features from the
input image and Residual patch data will be
calculated. The proposed architecture uses
shallow Neural Network which significantly
enhances the computational time. It will extracts
more information using residual patch map data
to restore lost image details. The proposed
model is better than the existing CNN models in
terms of accuracy and computational time and it
is significantly faster than existing models in
terms of batch processing.

## Samples
### Input
![input_Image](/model/3309.jpg "Input Image")
### Output
![Output_image](/model/output_filename_33039.jpg "Output Image")

## Training
The proposed model uses BCDS300 dataset
where dataset consists of 200 images for training
model and 100 images for testing model. For the
training process, the model uses mean square
error (MSE) for error computation.

### Resudal  Patch Data
Second, in the system, the data loss is
significantly lesser. The size of the feature map
does not get reduced by the time when
Convolutional operation is used, unlike the
existing system. As in the model shallow neural
network consisting of only 3 layers combined
with input and the output layer due to which it
reduces the data loss while training.

## How to Run The Code
open training.ipynb file and run the code it will start the training process.

## How to Use
open output.ipynb file and change the inout file name and the output file name and the check the path correctly to run the cod.
then it will create an output image wil the name provided in the path given

