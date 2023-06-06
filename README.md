# OCR-OCV using-Mask-RCNN-using-Custom-Dataset
Create folder : Dataset

In Dataset folder create 2 folders : train and val Put training images in train folder and validation images in Val folder.
Make a parent folder Mask-rcnn in which dataset folder and all files on this repositories will be there.

For Annotation use VGG annotator and use polygons shapes only.

Download mrcnn folder from this repository: https://github.com/matterport/Mask_RCNN

Download coco weights : https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5

Now on commant prompt change the directory path where the mask-rcnn is present and in custom.py file add all the classes you want to use or present in your dataset.
After running requirement.txt file run python custom.py and training will be started with a logs folder created in which weights will be saved.

Using test file you can check you model.
