# 🌟 Edge Detection using Canny Algorithm

## 📌 Overview
This project implements the **Canny Edge Detection** algorithm from scratch using Python. The algorithm is compared with OpenCV's built-in function to evaluate performance and accuracy.

---

## 🖼️ Original Picture
![Original](https://github.com/user-attachments/assets/f1dfdb6b-a292-463b-be4a-475c53a34125)

---

## 🔍 Algorithm Steps
### 1️⃣ Convert Image to Grayscale
Reduces complexity and focuses on intensity changes.  
![Grayscale](https://github.com/user-attachments/assets/4fe124f7-6e8c-4b22-ae9d-df1c9398d991)

### 2️⃣ Apply Gaussian Filter
Smoothens the image to reduce noise.  
![Gaussian](https://github.com/user-attachments/assets/6bfbb756-3b8f-4c7a-873b-963b16b07ac6)

### 3️⃣ Compute Image Gradient
Uses Sobel filters to find intensity changes.  
![Sobel](https://github.com/user-attachments/assets/ebb66fac-51f1-4123-9853-295f7787afe5)

### 4️⃣ Non-Maximum Suppression
Thins out the edges to highlight only the strongest ones.  
![Suppression](https://github.com/user-attachments/assets/134aea6b-09de-476a-97b5-38f4edbf9b42)

### 5️⃣ Double Thresholding
Classifies edges into strong and weak edges.  
![Thresholding](https://github.com/user-attachments/assets/b3ff292c-a491-4d2b-8693-5a3bc0c5c128)

### 6️⃣ Edge Tracking by Hysteresis
Ensures weak edges connected to strong edges are preserved.  
![Tracking](https://github.com/user-attachments/assets/2ae06b35-e705-4187-87e1-e688f4a294c3)

### 7️⃣ Comparison with OpenCV
Compares results with OpenCV's built-in function.  
![Pumpkin](https://github.com/user-attachments/assets/163205cc-5380-42b4-bea5-a78f93022396)  
![Albert](https://github.com/user-attachments/assets/c512de56-884e-4e1e-91f2-40bc95d41a74)  
![Pumpkin Comparison](https://github.com/user-attachments/assets/181ed67c-5bb7-4806-9181-7e6c2e7a681b)  
![Albert Comparison](https://github.com/user-attachments/assets/d586e13f-ecdc-4619-9855-9628c14c07be)  

---

## 📊 Results
- ✅ Custom implementation closely matches OpenCV's results.
- ✅ Minor differences in edge detection accuracy.

## 🔥 Conclusion
- Our implementation closely follows the standard Canny algorithm.
- Performance is comparable to OpenCV's built-in function.
- Can be further optimized for speed and efficiency.

---

## 🛠️ Technologies Used
- 🐍 Python
- 📷 OpenCV
- 🔢 NumPy
- 🔬 SciPy
- 📊 Matplotlib
- 🖼️ Scikit-Image

## ⚙️ Installation
1️⃣ Clone the repository:
   ```sh
   git clone https://github.com/milutinnedeljkovicc/Canny-implementation.git
   cd Canny-implementation
   ```
2️⃣ Install required dependencies:
   ```sh
   pip install numpy opencv-python scipy matplotlib scikit-image pandas
   ```

## 🚀 Usage
1️⃣ Run the script to apply the Canny Edge Detection algorithm:
   ```sh
   python canny_edge_detection.py
   ```
2️⃣ The script will process images and display the detected edges.

---
