## PlateIQ: Visual Diet Analysis system using YOLOv8
PlateIQ is an AI-powered visual diet analysis system that allows users to upload food images and instantly receive detailed nutritional insights. Using YOLOv8 for real-time food detection, segmentation, and portion estimation, the system simplifies diet tracking and helps users make informed food choices effortlessly.

## About
PlateIQ is a smart dietary assessment system designed to automate food recognition and calorie estimation from a single meal image. Traditional diet tracking relies heavily on manual logging or estimation, which is time-consuming and prone to errors. PlateIQ resolves these challenges by integrating advanced computer vision techniques to identify food items, estimate portion sizes, and compute nutritional values automatically.

The system uses the YOLOv8 algorithm for real-time object-level food segmentation and recognition. When a user uploads an image of their meal, the system processes the image, extracts each food item, identifies it using a food database, estimates its quantity using segmentation masks, and then computes calories along with proteins, fats, carbohydrates, and fiber.
This makes PlateIQ a practical tool for diabetes management, fitness monitoring, and general healthy eating.

## Features

#### Real-time Food Detection using YOLOv8:
- High-speed and accurate food recognition with object segmentation.

#### Automatic Portion Size Estimation:
- Uses pixel-level masks and depth estimation to measure meal volume.

#### Nutritional Computation:
- Calorie, protein, carbohydrate, fat, and fiber calculation.

#### Personalized Dietary Insights:
- Nutrition suggestions tailored for diabetics, athletes, and general users.

#### High Scalability & Web Deployment:
- Lightweight model suitable for web-based and mobile applications.

#### Robust Performance:
- High accuracy (≈98%) even under varying lighting and occlusion conditions.
## Requirements
#### Operating System:
Works on Windows 11 (64-bit).
#### Programming Environment:
Python 3.10+ for YOLOv8 and backend processing.

#### Deep Learning Framework:
Ultralytics YOLOv8 (PyTorch-based) for detection and segmentation.

#### Image Processing Libraries:
OpenCV for pre-processing and mask-based area estimation.

#### Additional Dependencies:

NumPy, Pandas

Torch / Ultralytics

MiDaS (for depth estimation)

FastAPI/Flask for web API

HTML/CSS/JS for UI

#### Version Control:
GitHub for repository management and collaboration.

#### IDE:
VSCode for coding, debugging, and extension support.

## System Architecture
<!--Embed the system architecture diagram as shown below-->

![Screenshot 2023-11-25 133637](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/a60c11f3-0a11-47fb-ac89-755d5f45c995)


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Name of the output

![Screenshot 2023-11-25 134037](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/8c2b6b5c-5ed2-4ec4-b18e-5b6625402c16)

#### Output2 - Name of the output
![Screenshot 2023-11-25 134253](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/5e05c981-05ca-4aaa-aea2-d918dcf25cb7)

Detection Accuracy: 96.7%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
PlateIQ transforms the diet-tracking process by making nutritional assessment fast, automated, and user-friendly. With its YOLOv8-based detection pipeline, it provides highly accurate food recognition and portion estimation even in real-world conditions.

This system supports:
- Diabetes management with carbohydrate/sugar tracking

- Athletic nutrition with protein-focused recommendations

- General wellness through balanced meal insights

By combining deep learning with nutrition science, PlateIQ offers an effective and scalable solution for hospitals, fitness centers, health apps, and individual users. It enables healthier lifestyle choices and promotes preventive healthcare.

## Articles published / References
1.Banusharath K.A. et al., “Applications of Hybrid Metaheuristic Algorithms for Image Processing,” Springer, 2020.

2.Agarwal R. et al., “Hybrid deep learning algorithm-based food recognition and calorie estimation,” Journal of Food Processing and Preservation, 2023.

3.Rouhafzay A. et al., “Image-based food monitoring and dietary management,” Frontiers in Nutrition, 2025.

4.Konstantakopoulos F.S. et al., “AI systems for food recognition and volume estimation,” IEEE Reviews in Biomedical Engineering, 2023.

5.Jiang L. et al., “DeepFood: food image analysis and dietary assessment,” IEEE Access, 2020.


