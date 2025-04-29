
# 🌑 Low Light Image Enhancement for Lunar and PSR Imagery

This project enhances low-light images, specifically designed for **lunar crater analysis** and **permanently shadowed regions (PSRs)** on the moon. The enhancement pipeline combines classical and deep learning-based methods to improve visual clarity under challenging lighting conditions.

---

##  Features

-  **BM3D Denoising**: A powerful block-matching algorithm for removing image noise while preserving details.  
-  **Deep Learning-based Sharpening**: Convolutional neural network (CNN) model to enhance edge details in dark regions.  
-  **Image Preprocessing Pipeline**: Includes sharpening, normalization, and denoising techniques optimized for moon surface analysis.  
-  **Support for Multiple Image Formats**: Tested with a variety of moon crater image datasets.  

---

##  Technologies Used

- Python  
- OpenCV  
- TensorFlow / Keras  
- NumPy  
- BM3D (custom implementation)  

---

##  Directory Structure

```
bm3d/
├── bm3dmodel.py         # Main enhancement and BM3D logic  
├── inputimage/          # Sample lunar crater images  
├── .idea/               # Project config (for PyCharm IDE)  
model.py                 # CNN model for image sharpening  
```

---

##  How It Works

1. Input images are loaded and sharpened using a convolutional filter.  
2. A deep CNN model enhances image details through residual learning.  
3. BM3D denoising is applied to reduce low-light image noise.  
4. Final output produces clearer visual data, useful for scientific analysis of PSRs and craters.  

---

##  Getting Started

```bash
git clone https://github.com/your-username/low-light-lunar-enhancement.git
cd low-light-lunar-enhancement
pip install -r requirements.txt
python bm3dmodel.py
```

---

##  Sample Images

The `inputimage/` folder includes raw lunar crater samples to test the pipeline.

---

##  Applications

- Lunar lander navigation systems  
- Space-based scientific imaging  
- PSR terrain mapping and rover planning  
- Astronomy research and analysis  
```

