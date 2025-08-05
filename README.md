# 🍽️ Food Recognition & Calorie Estimation
A Deep Learning project for detecting food items and estimating their calories

--------------
###  Overview
This project uses deep learning models to:
1-Recognise food items from images using EfficientNet (classification).
2-Detect multiple foods in a single image using YOLOv5 (object detection).
3-Estimate calories based on detected food items using a nutritional dataset (NutritionVerse / Nutrition5k).
The application can be used for:
•Health tracking & diet monitoring
•Meal logging apps
•Smart calorie estimation for nutrition planning

--------------
### 📊 Datasets
Food‑101
•101 food categories
•101,000 images
•Used for classification (EfficientNet) and detection (YOLOv5)

--------------
### Models Used
EfficientNetB0 (Transfer Learning)
•Classifies food images into 101 categories (Food‑101 dataset)
YOLOv5s (Object Detection)
•Detects multiple food items in one image
Calorie Estimation
•Matches detected classes to calorie values from a nutrition dataset
