# SDA-OpenCV
This project uses OpenCV HOGDescriptor to detect people, calculate their distances from each other, and alert if they are close enough.

Algorithm:

1. Find people using OpenCV HOGDescriptor
2. Apply non-maxima suppression to the bounding boxes
3. Calculate the center of each bounding box of detected people
4. Check the distance of people
5. Draw red bounding boxes for who are close to each other
