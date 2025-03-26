![CancerMe Banner](assets/A_GitHub_banner-style_digital_illustration_designe.png)

# CancerMe – AI Skin Cancer Detection  
**Author**: Aralbek Altynay  
**Prototype project using deep learning and Gradio (Colab-based)**  

## 🧬 Overview  
**CancerMe** is a prototype for skin cancer detection using deep learning and a simplified AI interface built with **Gradio**.  
It allows users to upload dermatoscopic images (e.g. mole photos) and receive a class prediction based on the **HAM10000** dataset.

This is not yet a standalone web app — it currently runs in **Google Colab** as a proof of concept and can be used directly from within a notebook.


## ✅ What Makes It Unique?

- 🔬 **Built from scratch** using raw dataset and image preprocessing  
- 🧠 Trained a **custom Convolutional Neural Network (CNN)**  
- 📊 Evaluated model with test metrics and class balance analysis  
- 🖼️ Includes **random image prediction testing block** (visual + prediction)  
- 🌐 **Interactive interface using Gradio**, allowing non-programmers to use the model  
- 💡 Clean interface, author name included, easy to expand into a full web app  

## 🗂 Dataset Used  
- **HAM10000 (Human Against Machine)**  
- Source: [Kaggle – skin-cancer-mnist-ham10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)  
- License: **CC BY-NC-SA 4.0**
- 
## 🔎 Target Classes

Model classifies images into the following skin lesion types:

- `akiec`: Actinic keratoses  
- `bcc`: Basal cell carcinoma  
- `bkl`: Benign keratosis  
- `df`: Dermatofibroma  
- `mel`: Melanoma  
- `nv`: Melanocytic nevi  
- `vasc`: Vascular lesions

## ⚙️ How to Run the Prototype  

1. Open the notebook `skin-cancer-detector.ipynb` in **Google Colab**  
2. Run the cells sequentially to load and preprocess data, train the model and launch Gradio  
3. Use the upload button in the Gradio UI to test your own image  
4. You’ll see the predicted class displayed instantly  

## 📌 Author Contribution

This notebook was:

- Modified and extended from the original Kaggle dataset  
- Model trained and tuned from scratch  
- Gradio interface added manually  
- Organized, visualized and deployed in Colab by **Aralbek Altynay**

## 🌐 License & Acknowledgements

- Dataset by Tschandl et al., used under **CC BY-NC-SA 4.0**  
- Notebook created for educational and experimental purposes  
- Please cite the dataset if re-used in future work


## 🚧 Future Work  
- Turn this prototype into a web app with deployment (e.g. Hugging Face Spaces, Streamlit Cloud)  
- Improve model accuracy and add confidence scores  
- Include bounding box detection and image augmentation pipeline  
