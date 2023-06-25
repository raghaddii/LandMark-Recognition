# LandMark-Recognition
Building model to automatically predict the location of the image based on any landmarks depicted in the image

# Dataset
The dataset used in this work is https://udacity-dlnfd.s3-us-west-1.amazonaws.com/datasets/landmark_images.zip 
 collected from 50 possible landmarks from across the world, the images toke from different directions for the same landmark , which contains images annotated with labels representing human-made and natural landmarks. 
 it’s split into training and test folders. Each folder contains 50 landmark that contain 100 image in train , 25 image in test for each of these landmarks.
# Result
- First stage after training CNN from scratch:
  
Test Loss: 2.678351

Test Accuracy: 30% (379/1250)
- Second stage after training CNN using transfer learning :
  
Test Loss: 0.817087

Test Accuracy: 80% (1004/1250)
