## Tools for Object detection 

### Illustrations-training.ipynb
Training of model to detect bounding boxes for illustrations identified in the image. Based on Mask R-CNN instamce segmentation method as implemented 
as part of the detectron2. Uses transfer learning and pre-trained weights are taken from PubLayNet model zoo<br>
Input:<br>
Dataset in COCO format <br>

Output:<br>
detection model

Note: Due to some compatibility issues copy pre-trained weights to your local system from 
https://www.dropbox.com/s/dgy9c10wykk4lq4/model_final.pth?dl=1
