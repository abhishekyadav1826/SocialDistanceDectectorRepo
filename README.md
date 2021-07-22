# SocialDistanceDectectorRepo
This project can be used for checking how well the social distancing norm is followed by the people.
There are mainly three step 
step 1 - object detection 
For object detection the yolo algorithm is used which can detect approx 9000 object clases 
The coco data set is used which can detect 80 different labels in which person class is also including 
step -2 object tracking 
For object detection euclidiean distance is measure from every old object(person) to new object and all close pair are detected as same person.
step 2- distance measurement 
For distance measurement the D' = (W*F)/P  formula is used 
     Where ,   D= distance
               W = width of the object
               F= focal length of the camera
               P = distance in pixel
The libraries used in this project are numpy, argparese, scipy, imutils & opencv.
