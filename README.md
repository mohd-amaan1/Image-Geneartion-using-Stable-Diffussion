
# Image Generation using Stable Diffusion & ComfyUI  

![Generated Output](./output_image.jpg)  

## 📌 Project Overview  
This project demonstrates **AI-powered image generation** using **Stable Diffusion** with **ComfyUI**, a **node-based graphical interface** for workflow-based AI image generation. The goal is to provide an **interactive and user-friendly environment** for generating high-quality AI-generated images from text prompts.  

## 🚀 Features  
✅ **Text-to-Image Generation** using Stable Diffusion  
✅ **Node-Based Workflow** via ComfyUI  
✅ **Customizable Parameters** for fine-tuned image generation  
✅ **Denoising & Upscaling** for improved image quality  
✅ **Supports NVIDIA CUDA for GPU acceleration**  

## 📷 Output Image Example  
Below is an example of an AI-generated image using a **text prompt**:  

![AI Generated Image](./output/ComfyUI_00001_.png)  

## 🔧 Installation & Setup  
### **1️⃣ Prerequisites**  
Ensure you have the following installed:  
- Python **3.8+**  
- NVIDIA GPU (Recommended) with **CUDA support**  
- **Git** for cloning the repository  

### **2️⃣ Clone the Repository**  
```bash
git clone https://github.com/mohd-amaan1/Image-Geneartion-using-Stable-Diffussion.git
cd Image-Geneartion-using-Stable-Diffussion
```

### **3️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **4️⃣ Run ComfyUI**  
```bash
python server.py
```
Then, open **http://localhost:8188** in your browser to access the ComfyUI interface.  

## 🛠️ Tools & Technologies Used  
- **Stable Diffusion** - AI-powered text-to-image generation  
- **ComfyUI** - Graph-based UI for workflow automation  
- **PyTorch** - Deep learning framework  
- **CUDA** - GPU acceleration  

## 📌 Future Enhancements  
🔹 Support for **ControlNet** for better image structuring  
🔹 Add **text-to-video generation** using AI models  
🔹 Deploy as a **web-based API for broader access**  

## 📜 License  
This project is licensed under the **MIT License**.  

