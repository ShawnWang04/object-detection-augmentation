## object-detection-augmentation-This contains some data augmentation methods for target detection algorithms. Such as mosaic and mixup.
---

## Directory
1. [Data augmentation test](#Data augmentation test)
2. [Generate images and labels](#Generate images and labels)

## Data augmentation test
Several py files starting with test are used to test different data augmentation methods.
### Test steps
1. Origin_VOCdevkit_path is used to specify the folder where the VOC dataset is located;
2. input_shape represents the size of the image after data augmentation;
3. Run test_*.py to view the corresponding data augmentation effect.

## Label processing
Several py files starting with generate are used to generate and save labels and images after data augmentation.
### Generation steps
1. Origin_VOCdevkit_path is used to specify the path of the dataset to be enhanced;
2. Out_VOCdevkit_path is used to specify the output dataset path;
3. Out_Num is used to enhance the number of images generated;
4. input_shape represents the size of the image after data augmentation;
5. Run generate_.py to generate and save the labels and images after data augmentation.
