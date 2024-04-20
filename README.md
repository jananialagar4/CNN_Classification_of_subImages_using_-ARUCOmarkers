# CNN_Classification_of_subImages_using_-ARUCOmarkers
A CNN model for capturing subimages in an image and classify them into subgroups with the help of ArUco Markers.
<hr>

File: model(inception).ipynb
- Transfer Learning model - Inception
- Dataset - 5 subgroups of images (Military, Humanitarian aid, Rehabilitation, Fire, Destroyed Buildings)

File: Classification of sub images(5 subgroups) using Aruco Markers.ipynb
- Extraction of roi (sub images) from original image using ArUco Markers
- Increased resolution of roi using EDSR_x3.pb
- Classifying roi into 5 sub groups with model trained previously
- Applying text and bounding box over roi in original image after classification with their respective predicted sub group classes
  

