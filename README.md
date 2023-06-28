# Detect Parking Lot Occupancy using Tensorflow, OpenCV, and SVC

*I leverage Tensorflow (Keras), OpenCV, and SVC to predict real-time parking spot availability. I have provided a demo video on Youtube, below:*
[![Automatically Detect Parking Lot Occupancy using Real-Time Ariel Footage](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*fLdGL7Q5HSbRpwoz5St19A.png)](https://www.youtube.com/watch?v=8jPV7NW326w "[Youtube] Automatically Detect Parking Lot Occupancy using Real-Time Ariel Footage")
*Demo Video: [https://www.youtube.com/watch?v=8jPV7NW326w](https://www.youtube.com/watch?v=8jPV7NW326w)*
*Full Article: [Detect Parking Lot Occupancy using Tensorflow, OpenCV, and SVC](https://medium.com/@yohmori/parking-lot-space-detection-60712dc5d1c7)*


## 1. Introduction
Efficient management of parking lots in urban areas is not only a matter of convenience but also a crucial aspect of optimizing limited space resources. The ability to accurately detect and classify parking lot occupancy has significant implications for improving parking availability, reducing traffic congestion, and enhancing overall urban mobility.

## 2. Files
- **1_data_augmentation.ipynb:** Given a few training images in /empty and /full, augment 3,000 images each.
- **2_create_model.ipynb:** Given new 3,000 x 2 images, train model
- **3_main.ipynb:** Given trained model, test on video
- **data:** Training data
- **model:** Trained model used


## 3. How to use
Run 1_data_augmentation.ipynb
Run 2_create_model.ipynb
Run 3_main.ipynb