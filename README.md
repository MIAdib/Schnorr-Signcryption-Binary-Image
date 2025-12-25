# 🧩 Schnorr Signcryption for Black-and-White Image Encryption

![Python](https://img.shields.io/badge/Python-3.10-blue)
![License: MIT](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

> **Final Year Project (FYP)** – Universiti Teknologi MARA (UiTM)  
> **Author:** Mohamad Izzul Adib Bin Shamsudin  
> **Supervisor:** Sir Nizam Udin  
> **Field:** Cryptography and Image Security  

---

## 🧠 Abstract / Overview

This project presents an **enhanced implementation of the Schnorr Signcryption scheme** for **black-and-white image encryption**.  
The system integrates **signature and encryption** in a single process to achieve **data confidentiality, authenticity, and computational efficiency**.

The goal is to explore how the Schnorr Signcryption mechanism can be effectively adapted to **binary image data**, with a focus on performance, key generation, and message reconstruction accuracy.

---

## ✨ Key Features

- 🔒 **Integrated Signcryption:** Combines encryption and digital signature in one operation.  
- 🖼️ **Image-Based Encryption:** Supports black-and-white image inputs as messages.  
- ⚡ **Efficient Computation:** Optimized for lightweight image data processing.  
- 🔑 **Ephemeral Key Mechanism:** Introduces randomness for each session to enhance forward secrecy.  
- 📊 **Performance Analysis:** Includes runtime comparison and efficiency metrics.

---

## ⚙️ Methodology

1. **Image Preprocessing:** Convert black-and-white images into binary (0,1) and integer representations.  
2. **Key Generation:** Generate public and private key pairs.  
3. **Signcryption Phase:**  
   - Generate an ephemeral key.  
   - Compute ciphertext and digital signature simultaneously.  
4. **Unsigncryption Phase:**  
   - Verify signature authenticity.  
   - Decrypt the image data.  
5. **Reconstruction:** Convert decrypted integers back into black-and-white image format.

### 📘 Workflow Diagram
![Workflow Diagram](docs/workflow_chart.png)

---

## 🧰 Technologies Used

- **Language:** Python 3.x  
- **Libraries:** NumPy, OpenCV, hashlib, time, matplotlib  
- **Tools:** Google Colab / Jupyter Notebook  
- **Documentation:** Microsoft Word, PowerPoint  

---

## 🚀 Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/AdibXYZ/Schnorr-Signcryption-Image-Encryption.git

# 2. Navigate to the folder
cd Schnorr-Signcryption-Image-Encryption

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the main program
python src/main.py
