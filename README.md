# Human Body Detection using cascade classifier     

We can extract features like head, two arms, two legs, etc, from an image of a human body and pass them to train a machine learning model. After training, the model can be used to detect and track humans in images and video streams. However, OpenCV has a built-in method to detect pedestrians. It has a pre-trained HOG(Histogram of Oriented Gradients) + Linear SVM model to detect pedestrians in images and video streams.     

Haar Cascade Classifiers : We will implement our use case using the Haar Cascade classifier. Haar Cascade classifier is an effective object detection approach which was proposed by Paul Viola and Michael Jones in their paper, “Rapid Object Detection using a Boosted Cascade of Simple Features” in 2001.

   
![](https://pyimagesearch.com/wp-content/uploads/2015/11/pedestrian_detection_person_265.jpg)    

![](https://www.goeduhub.com/?qa=blob&qa_blobid=16797505939970783078)       

---
### Technologies Used:
**Languages Used-** python     
**Libraries Used -**
- numpy
- time
- cv2
- argparse

---

### Installation and setup
1. First clone this repo using the link https://github.com/Zeo-shark/Body-Detection-using-cascade.git.
2. cd Body-Detection-using-cascade.
3. pip install -r requirements.txt.   
4. python app.py.

