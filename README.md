
# Experimental validation of computer-vision methods for the successful detection of endodontic treatment obturation and progression from noisy radiographs

Link to the [Published Paper](https://link.springer.com/article/10.1007/s11282-023-00685-8) in Springer

## Purpose
1. To evaluate the effects of denoising and data balancing on deep learning to detect endodontic treatment outcomes from radiographs. 
2. To develop and train a deep-learning model and classifier to predict obturation quality from radiomics.
## Classes
1. Class 1: No endodontic treatment performed
2. Class 2: Incomplete endodontic obturation performed
3. Class 3: Suboptimal endodontic treatment
4. Class 4: Complete endodontic obturation performed

## Methods
The study conformed to the STARD 2015 and MI-CLAIMS 2021 guidelines. 250 deidentified dental radiographs were collected and augmented to produce 2226 images. The dataset was classified according to endodontic treatment outcomes following a set of customized criteria. The dataset was denoised and balanced, and processed with YOLOv5s, YOLOv5x, and YOLOv7 models of real-time deep-learning computer vision. Diagnostic test parameters such as sensitivity (Sn), specificity (Sp), accuracy (Ac), precision, recall, mean average precision (mAP), and confidence were evaluated.



## Results
Overall accuracy for all the deep-learning models was above 85%. Imbalanced datasets with noise removal led to YOLOv5x’s prediction accuracy to drop to 72%, while balancing and noise removal led to all three models performing at over 95% accuracy. mAP saw an improvement from 52 to 92% following balancing and denoising.
## Screenshots
![App Screenshot](https://media.springernature.com/full/springer-static/image/art%3A10.1007%2Fs11282-023-00685-8/MediaObjects/11282_2023_685_Fig8_HTML.jpg?as=webp)
## Conclusion
The current study of computer vision applied to radiomic datasets successfully classified endodontic treatment obturation and mishaps according to a custom progressive classification system and serves as a foundation to larger research on the subject matter.



## Authors

- [@igenhimel](https://www.github.com/igenhimel)

- [@saadism777](https://www.github.com/saadism777)

