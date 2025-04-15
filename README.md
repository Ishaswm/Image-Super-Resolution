# 🖼️ Image-Super-Resolution

Enhance the quality and resolution of low-resolution images using deep learning-based **Enhanced Super-Resolution Generative Adversarial Network (ESRGAN)**. This project explores cutting-edge super-resolution techniques and implements ESRGAN using TensorFlow.

# 🚀 Project Overview
This project aims to upscale low-resolution images while preserving fine details and improving sharpness. It uses ESRGAN – a state-of-the-art model designed specifically for image super-resolution tasks. The model is loaded from TensorFlow Hub, and implemented using OpenCV, TensorFlow, and Matplotlib.

# 🎯 Objectives
1. Enhance visual quality and clarity of images.
2. Retain texture and fine details in high-resolution outputs.
3. Provide a practical, easy-to-use tool for super-resolution.
4. Evaluate model performance with visual and quantitative metrics.

# 🧠 Technologies Used

Tool/Library | Purpose
TensorFlow | Deep learning framework
TensorFlow Hub | Pretrained ESRGAN model
OpenCV | Image reading & preprocessing
NumPy | Numerical operations
Matplotlib | Displaying image output
PIL (Pillow) | Image format manipulation

# 🧪 Methodology
1. Load image using OpenCV and convert BGR to RGB.
2. Preprocess image: resize and crop to fit ESRGAN’s requirements.
3. Load ESRGAN model from TensorFlow Hub.
4. Pass preprocessed image through the model to generate a high-res output.
5. Display and compare results using Matplotlib.

# 📊 Results
1. Achieved high perceptual quality and detail enhancement.
2. SSIM scores confirmed superior structural similarity.
3. ESRGAN outperformed traditional interpolation and SRGAN in clarity, sharpness, and edge detail.
<img width="643" alt="Screenshot 2025-04-15 at 9 16 21 PM" src="https://github.com/user-attachments/assets/20053028-5406-4c8a-99e9-2f2decc0846d" />
<img width="402" alt="Screenshot 2025-04-15 at 9 16 47 PM" src="https://github.com/user-attachments/assets/5e6c694a-6b1a-4734-b3c3-20ad7902a03d" />

# 📈 Future Improvements
1. Expand dataset diversity for better generalization.
2. Explore model fine-tuning for domain-specific use (medical/satellite).
3. Optimize for low-end devices by reducing computational complexity.

# 📜 References

- [ESRGAN Paper](https://arxiv.org/abs/1809.00219)  
- [TensorFlow Hub ESRGAN](https://tfhub.dev/google/esrgan/1)  
- [OpenCV Documentation](https://docs.opencv.org/)  
- [Pillow Library](https://pillow.readthedocs.io/)







