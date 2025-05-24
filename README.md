# Diffusion Models

This repository contains the code and results for our term project in the **UMC203: Introduction to AI and ML** course at **IISc**.

## 📌 Contributors
- [Om Prakash Choudhary](https://github.com/Om2005Prakash)  
- [Himesh Kumar Anant](https://github.com/himeshanant)  
- [Jithendra Rao Kasibhatla](https://github.com/jithendra085)
- [Keval Pithadiya](https://github.com/kevalpithadiya)

---

## 🧪 Results

### CelebA 128x128 – Noise Prediction  
<p align="center">
  <img src="./Samples/CelebA128/CelebA_Noise_DDPM_Samples.png" width="45%"/>
  <img src="./Samples/CelebA128/CelebA_Noise_DDIM_Samples.png" width="45%"/>
</p>

---

### CIFAR-10 32x32  
#### Noise Prediction  
<p align="center">
  <img src="./Samples/CIFAR10/CIFAR10_Noise_DDPM_Samples.png" width="45%"/>
  <img src="./Samples/CIFAR10/CIFAR10_Noise_DDIM_Samples.png" width="45%"/>
</p>

#### Clean Image Prediction and Score Matching  
<p align="center">
  <img src="./Samples/CIFAR10/CIFAR10_Clean_DDPM_Samples.png" width="45%"/>
  <img src="./Samples/CIFAR10/CIFAR10_Score_Samples.png" width="45%"/>
</p>

---

### Miscellaneous  
#### Sampling Progress vs. Number of Steps | Latent Interpolation  
<p align="center">
  <img src="./Samples/misc/progress_with_steps.png" width="45%"/>
  <img src="./Samples/misc/interpolation128_upd.png" width="45%"/>
</p>

---

## 🧠 Models Trained

We trained **Denoising Diffusion Probabilistic Models (DDPMs)** using Hugging Face's `diffusers` library for both noise prediction and clean image prediction objectives.

### 📊 Datasets and Resolutions
- **CIFAR-10**: 32×32  
- **CelebA**: 32×32 and 128×128  
- **MNIST**: 32×32  

### 🔗 Pretrained Models
- 📁 [Google Drive Folder](https://drive.google.com/drive/folders/1HmLK4hkkI6-Fl6vaHyX05PBe8U2FWl5E?usp=drive_link)  
- 🤗 [HuggingFace Model Hub](https://huggingface.co/Om2005Prakash/Diffusion_Pre_Trained/tree/main)

---

## 🛠️ Setup Instructions

### Install Dependencies
```bash
pip install diffusers[training]
