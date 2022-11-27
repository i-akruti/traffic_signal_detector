# traffic_signal_detector

#### Using only opencv

## Steps followed

1. Pre-process the image by thresholding the image and dilating.
2. Find all rectangular contours
3. In all rectangular contours found, find the percentage of illiminated area. If, the rectangle is ~30-33% illuminated, then it can be said it is a traffic light. 
4. In all traffic light candidates, divide the rectangle into 3 sections. And decide the signal based on which section is illuminated.
