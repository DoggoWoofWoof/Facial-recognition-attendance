To use this replace all the paths to the respective paths in the user filesystem
Running create dataset takes set amount of pictures and stores it in the filesystem, change the values such as path and count of pictures to make a proper dataset
Train model trains the model based on the dataset and stores the h5 model path file which can be changed to the .keras path file as .keras is newer, make sure to change the same in display dataset
display dataset uses the pre trained model and HAAR classifier to detect and identify the faces

Sources:
https://pyimagesearch.com/2021/04/05/opencv-face-detection-with-haar-cascades/
https://datagen.tech/guides/computer-vision/vgg16/#
