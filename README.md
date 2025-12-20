# Project Chimera v1.0: The Digital Antidote 🛡️
**Iterative Adversarial Masking for Biometric Identity Protection**

## 📌 Overview
Project Chimera is a security research project focused on **Adversarial Machine Learning**. It aims to reclaim biometric sovereignty by generating a mathematical "cloak" that renders images unidentifiable to specialized facial recognition systems while remaining visually unchanged to the human eye.

## 🚀 The Problem: Biometric Scraping
Modern AI models (CNNs/Vision Transformers) convert faces into high-dimensional feature vectors. These models are highly sensitive to high-frequency digital noise that humans cannot perceive. Chimera exploits this "blind spot" to protect personal privacy.

## 🛠️ Technical Methodology
Chimera v1.0 utilizes **Projected Gradient Descent (PGD)** to find optimal noise perturbations. 
* **Iterative Attack:** Refines the adversarial mask over 10+ iterations to maximize model confusion.
* **Epsilon Constraint:** Keeps the "noise" within a strict $\epsilon$-ball, ensuring the photo remains usable for social media.

## 📸 Results
| Input Image | Adversarial Mask | Protected Output |
| :--- | :--- | :--- |
| [Insert your photo] | [Insert Chimera mask] | [Insert protected photo] |

## 💻 Installation & Usage
1. Clone the repo: `git clone https://github.com/hsprince-14/Project-Chimera-v1.git`
2. Install dependencies: `pip install numpy Pillow`
3. Run the script: `python main.py`
4. Prepare Your Image:-
`File Name: Rename your target photo to my_photo.jpg.`
`Placement: Move my_photo.jpg directly into the same root folder as the main.py script.`
5. Collect Your Results:-
The script will generate two new files in your project directory:
`chimera_shield_v2.png: The protected photo to be used for social media.`
`chimera_v2_mask.png: A visualization of the adversarial gradients used to blind the AI.`

## ⚖️ License
This project is for educational and research purposes only.
