# Challenge 1 - syn2syn

Classes: 330 classes  
Train: 13200 synthetic images  
Test: 1800 synthetic images (not available to competitor)

All images were generated in one go, and split afterwards. When generating the data, the goal was to have 100 instances per image, thus 13200 images should equate to 4000 instances per class.

Data to be used:
GDrive/common/train/syn/

Scripts to be used:
GDrive/common/evaluator.py - this will give you the score.

Submission:
- A CSV file with your predictions for the test data set
- The output should be in the same format as the annotations.csv file, that is as csv file where each line is: <imageid>,<xmin>,<ymin>,<xmax>,<ymax>,<class label>
- We will need to validate your Colab/other environment (to ensure no test data was used for training).

Challenge metric:  
We use the default COCO mAP object detection metric as described here: https://cocodataset.org/#detection-eval  
A helpful Medium post is: https://jonathan-hui.medium.com/map-mean-average-precision-for-object-detection-45c121a31173 

