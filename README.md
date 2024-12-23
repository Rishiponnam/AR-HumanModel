# AR-HumanModel

**AR-HumanModel** is an Augmented Reality (AR) mobile application designed to test vehicle designs by simulating human body shapes of diverse sizes and proportions. This app utilizes statistically accurate 3D body models that represent a wide variety of human body types, including men, women, and children, with a focus on anthropometric characteristics such as stature, age, BMI, and sitting height. These models were developed by the University of Michigan Transportation Research Institute (UMTRI) through the analysis of 3D laser scans of hundreds of individuals.

Built using **Unity3D** (Editor version: 2021.3.7f1) and the **Vuforia Unity SDK**, **AR-HumanModel** enables real-time manipulation of body shape models to test how well vehicle designs accommodate people of different body types. This tool provides an interactive and accurate visualization of body dimensions, making it an essential resource for improving vehicle ergonomics, safety, and comfort.

The app also allows users to view anatomical landmarks on the human body, making it a useful tool for research, design, and development in fields like automotive engineering, biomechanics, and AR technology.

Learn more about the accuracy and development of these models here: [HumanShape™](http://humanshape.org/)

---

## Features

- **Real-Time Body Shape Manipulation**: Adjust body dimensions such as BMI, age, stature, and sitting height.
- **Anatomical Landmark Visualization**: View key points on the human body for greater precision.
- **Statistically Accurate 3D Models**: Built from detailed laser scans of diverse populations.
- **Seamless AR Integration**: Utilize the power of AR to visualize body shapes directly in the real world.

---

## Setup Instructions

Before opening the **AR-HumanModel** Unity Project, please follow these steps:

1. **Download the Unity Editor (version 2021.3.7f1)**:
   - Ensure you're using Unity Editor version **2021.3.7f1** for compatibility.

2. **Prepare the Project Directory**:
   - Go to the **Packages** folder in the **AR-HumanModel** project directory.
   - Delete the **packages-lock** file to prevent conflicts.

3. **Install Vuforia SDK**:
   - Download the Vuforia package `com.ptc.vuforia.engine-10.9.3.tgz` from the repository.
   - Place the downloaded file in the **Packages** folder.

4. **Open the Project**:
   - You are now ready to open the Unity project.
   - If you encounter any errors related to the package cache, follow these steps:
     - Delete the specific folder mentioned in the error from the **cache** directory.
     - Delete the **packages-lock** file again.
     - Reopen the Unity project.

---


Thank you for using **AR-HumanModel**!