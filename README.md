# 🚀 **Denoising CSI in 5G RAN Using Generative Adversarial Networks (GANs)**  

## 📌 **Overview**  
This project focuses on **enhancing Channel State Information (CSI) in 5G Radio Access Networks (RAN)** using a **Denoising Generative Adversarial Network (DGAN)**.  

🔹 **Why CSI Denoising?**  
CSI is essential for **beamforming, link adaptation, and resource allocation** in 5G networks. However, **environmental noise, interference, and multipath fading** corrupt CSI measurements, leading to degraded network performance. Our GAN-based solution effectively **removes noise and reconstructs clean CSI**, ensuring **better reliability and communication quality**.  

---

## ✨ **Features**  
✅ CSI Denoising using **GANs**  
✅ Synthetic CSI Data Generation  
✅ Evaluation Metrics: **MSE, PSNR, SSIM**  
✅ Visualization of **Noisy vs. Denoised CSI**  
✅ **PyTorch** Implementation  

---

## 🔬 **Methodology**  

### 🛠 **1. Data Preparation**  
📌 **Simulating CSI Data:**  
- Generated synthetic CSI using **sine waves** with added **Gaussian noise**.  
- Converted CSI data into **PyTorch tensors** for deep learning processing.  

### 🤖 **2. Model Architecture**  
🟢 **Generator (G):** Learns to generate clean CSI from noisy input.  
🔴 **Discriminator (D):** Differentiates between real (clean) and fake (denoised) CSI.  

📝 **Loss Function:**  
- **Binary Cross-Entropy (BCE) Loss**  
- **Mean Squared Error (MSE)** for reconstruction accuracy  

### 🎯 **3. Training Process**  
- **Adversarial learning** is used to train the GAN.  
- Losses for **G and D are monitored** for convergence.  

### 📊 **4. Evaluation & Results**  
- Performance is measured using **MSE, PSNR, and SSIM**.  
- Visualized **Noisy, Clean, and Denoised CSI** for qualitative assessment.  

---

## 📈 **Results & Visualization**  

### 🔍 **Evaluation Metrics**  
| 📏 Metric | 📊 Value |
|-----------|---------|
| MSE       | 0.0084  |
| PSNR      | 20.75 dB |
| SSIM      | 0.85    |

📸 **Sample Visualizations:**  
🚧 *Noisy CSI → Denoised CSI (Using GANs)*  

---

## 📌 **Progress So Far**  
✅ **Occlusion Estimation Module** implemented  
✅ **Training completed** on synthetic CSI datasets  
🔄 **Fine-tuning GAN architecture** for better accuracy  

---

## 🤝 **Contributions**  
🔹 We welcome **collaborations and contributions**! Feel free to **fork, open issues, or submit pull requests**.  

---

## ⚖️ **License**  
📝 MIT License - Feel free to use, modify, and distribute this work!  

---

📢 **Stay Tuned for Further Updates! 🚀**
