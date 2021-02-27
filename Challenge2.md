# Challenge 2 - syn+real2real

Classes: 1 class (object)  
Train: 13200 synthetic images, 500 real images  
Test: 2936 test images (not available to competitor)

The synthetic training images are the same as from Challenge 1, however, all labels are now ‘object’.

Data to be used:
GDrive/common/train/syn/
GDrive/challenge-2/train/real/

Scripts to be used:
GDrive/common/evaluator.py - this will give you the score.

Submission:
- A CSV file with your predictions for the test data set
- The output should be in the same format as the annotations.csv file, that is as csv file where each line is: <imageid>,<xmin>,<ymin>,<xmax>,<ymax>,<class label>
- We will need to validate your Colab/other environment (to ensure no test data was used for training).

Challenge metric:  
We use the default COCO mAP object detection metric as described here: https://cocodataset.org/#detection-eval  
A helpful Medium post is: https://jonathan-hui.medium.com/map-mean-average-precision-for-object-detection-45c121a31173 
