# 🧠 Fake Currency Detection System 
*A Trustworthy Artificial Intelligence Course Project*

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-Image%20Processing-green.svg)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-orange.svg)
![AI Ethics](https://img.shields.io/badge/Trustworthy-AI-blueviolet.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

---

## 💡 Overview

The **Fake Currency Detection System** is a Trustworthy AI project designed to authenticate **Indian currency notes (₹500 & ₹2000)** using **image processing** and **computer vision techniques**. 
This system uses advanced algorithms for **feature extraction, pattern analysis, and similarity comparison** to determine whether a note is **real** or **fake**, prioritizing **accuracy**, **transparency**, and **explainability** in its decision-making.

It has been built completely in **Python** using:
- **OpenCV** for image processing 
- **Tkinter** for GUI development 
- **SSIM** and **ORB** algorithms for feature matching 
- **Jupyter Notebook** as the development environment 

---

## 🧩 Key Features

- 🔍 Detects counterfeit Indian currency of ₹500 and ₹2000 denominations 
- ⚙️ Utilizes **ORB (Oriented FAST and Rotated BRIEF)** for key feature detection 
- 📊 Measures similarity using **SSIM (Structural Similarity Index)** for comparison 
- 🖥️ User-friendly **Tkinter GUI** for interaction and visual results 
- 📁 Includes a custom, structured dataset of real and fake notes 
- 🧠 Built with **Trustworthy AI principles** — transparent, reliable, and explainable 

---

## 🛠️ Libraries and Tools

| Library / Tool | Purpose |
|----------------|----------|
| **OpenCV** | Image processing and core feature extraction |
| **Tkinter** | Graphical User Interface (GUI) for input and output |
| **NumPy** | High-performance numerical operations and array handling |
| **Matplotlib** | Visualization and plotting of data and features |
| **Jupyter Notebook** | Modular development, testing, and control flow |

---

## 📂 Project Structure

```yaml
Fake-Currency-Detection-System/
│
├── Dataset/
│ ├── Real_Notes/ # Real ₹500 and ₹2000 notes for templates
│ ├── Fake_Notes/ # Fake currency note images for testing
│ └── Features/ # Stored security feature templates
│
├── Fake Notes/ # Sample fake notes for testing
├── 500_testing.ipynb # Notebook for ₹500 detection logic
├── 2000_testing.ipynb # Notebook for ₹2000 detection logic
├── controller.ipynb # Main notebook controlling the workflow and GUI launch
├── gui_1.ipynb # GUI module for user input (Image selection, denomination)
├── gui_2.ipynb # GUI module for displaying detailed results
├── FAKE_CURRENCY_DETECTOR_REPORT.pdf # Complete project report
└── README.md # You are here!
```

---

## ⚙️ How to Run

### **Step 1: Setup and Initialization**

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/Fake-Currency-Detection-System.git](https://github.com/your-username/Fake-Currency-Detection-System.git)
    cd Fake-Currency-Detection-System
    ```
2.  **Open the project in Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
3.  **Run the main notebook:**
    * Open `controller.ipynb`
    * Click **Run All cells**.

---

### **Step 2: Use the GUI**

1.  A GUI window (`gui_1.ipynb`) will launch.
2.  Click **Select an Image** and choose a note image (sample images are in the `Dataset/` folder).
3.  Select the correct **denomination** (₹500 or ₹2000).
4.  Click **Submit**.

### **Step 3: View the Result**

1.  The system processes the image (~5 seconds).
2.  A new GUI window (`gui_2.ipynb`) displays the detailed authenticity report, scores, and final label.

---

## 📊 Results and Analysis

| Category | Notes Tested | Correctly Classified | Accuracy |
|---|---|---|---|
| Real Notes (₹500 & ₹2000) | 19 | 15 | 79% |
| Fake Notes | 12 | 10 | 83% |

⏱️ **Average Processing Time:** ~5 seconds per note

🧾 **Decision Rule:** If $\geq 9$ out of 10 security features pass the SSIM/count checks, the Note is classified as Genuine.

---

## 🔒 Trustworthy AI Principles

| Principle | Implementation in Project |
|---|---|
| **Transparency** | The system displays SSIM scores for each feature, showing the precise metrics used for the decision. |
| **Explainability** | Uses interpretable, rule-based computer vision metrics (SSIM, contour counts) instead of opaque black-box ML models. |
| **Reliability** | Built with deterministic algorithms and tested against a verified, custom dataset. |
| **Accessibility** | Designed with a user-friendly GUI for non-technical operators. |
| **Fairness** | Avoids human/data bias through consistent, objective, rule-based image analysis. |

---

## 🖼️ Demo (Screenshots)

To give a visual overview of the user experience:

1.  **Image Upload and Input Window**
    <img width="1471" height="826" alt="image" src="https://github.com/user-attachments/assets/89a53de1-a99c-45f0-8ece-b62d3060b15c" />

2.  **Processing Screen**
    <img width="1717" height="774" alt="image" src="https://github.com/user-attachments/assets/5c5fd577-d3a2-40c3-8729-b7b1bfab3cf2" />

3.  **Final Results Screen**
    <img width="425" height="822" alt="image" src="https://github.com/user-attachments/assets/feb7a9e8-4d4b-4281-aa1e-515d600cc375" />


---

## 🧭 Future Enhancements

* **🏦 Expand Denominations:** Extend support to include other notes (₹10, ₹20, ₹50, ₹100, ₹200).
* **🤖 Integrate Machine Learning:** Implement deep learning (e.g., CNNs) for automatic feature localization and recognition to improve robustness.
* **📱 Deployment:** Develop mobile and web-based versions for broader public and institutional use.
* **☁️ Cloud Validation:** Introduce cloud-based template verification for real-time validation and scalability.

---

## 👥 Contributors

| Name | Role |
|---|---|
| Maheswari Mudadla | Image Processing & GUI Design |
| Nihita Kolukula | Core Algorithm Development |
| Niyati Kolukula | Dataset Preparation & Testing |
| Aishwarya Para | Documentation & Integration |





---

## 🏁 Conclusion

The Fake Currency Detection System successfully demonstrates the application of Trustworthy Artificial Intelligence principles—namely **accuracy, interpretability, and accessibility**—to solve a real-world financial security problem. By robustly combining computer vision with ethical AI practices, this project delivers a scalable, transparent, and user-centric solution for counterfeit detection.
