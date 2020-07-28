# MASKD
___
### Problem Statement
The goal of this challenge is to train object detection models capable of identifying the location of masked faces in an image as well as the location of unmasked faces in the image. These detectors should be robust to noise and provide as little room as possible to accomodate false positives for masks due to the potentially dire consequences that they would lead to.

### Dataset
The dataset that would be used is from a combination of many sources, which have been hand-labelled. The dataset would contain annotations for masked and unmasked faces.

### Files:
* train_images.zip: This is the Training Set of 679 (as RGB images) images.
* train.json: This is the train annotations in MS-COCO format.
* val_images.zip: This is the suggested Validation Set of 120 (as RGB images) images.
* val.json: This is the val annotations in MS-COCO format.
* test_images.zip: This is the Test Set of 774 (as RGB images) images.
* test.json: This file contains the metadata of the test images including their filename,width,height,image_id.

### Evaluation Metric
**IoU(Intersection Over Union)**
IoU measures the overall overlap between the true region and the proposed region. Then we consider it a True detection, when there is atleast half an overlap, or when IoU > 0.5.

### Result
#### No. of Registered: 359
#### Rank: 11

[Leaderboard](https://www.aicrowd.com/challenges/aicrowd-blitz-2/problems/maskd/leaderboards?)<br/>
[Challenge Page](https://www.aicrowd.com/challenges/aicrowd-blitz-2/problems/maskd)<br/>
[Resources](https://www.aicrowd.com/challenges/aicrowd-blitz-2/problems/maskd/dataset_files)
