# ♻️ Trash Classification & Recyclability Prediction (ViT)

A lightweight ML project that classifies waste images and predicts whether the item is **recyclable or non‑recyclable** — powered by a fine‑tuned **Vision Transformer (ViT)**.

> Upload an image 👉 Model analyzes 👉 Get **material type + recyclability**

---

## ✨ Features
- 🚮 Multi‑class trash classification
- ♻️ Recyclability prediction
- 🤖 Vision Transformer backbone (transfer learning)
- ☁️ Easy to run in Google Colab
- 🧩 Clean, modular workflow

---

## 🧭 Overview (What the system does)
1️⃣ User uploads an image  
2️⃣ Image is preprocessed  
3️⃣ ViT model predicts the **trash category**  
4️⃣ Simple rules decide if it is **recyclable or not**  
5️⃣ Output is displayed to the user

---

## 📂 Dataset Structure
Organized by **recyclability first**, then by material:

```
dataset/
├── recyclable/
│   ├── paper/
│   ├── battery/
│   ├── e_waste/
│   ├── cardboard/
│   ├── white-glass/
│   ├── metal/
│   ├── brown-glass/
│   └── green-glass/
│
└── non_recyclable/
    ├── clothes/
    ├── shoes/
    ├── trash/
    ├── biological/
    └── plastic/
```

Each sub‑folder contains labeled images used for training and testing.

---

## 🧠 Approach
1. 📊 Clean and prepare dataset  
2. 🖼️ Resize images & split (train / val / test)  
3. 🔍 Load pretrained ViT model  
4. 🎯 Fine‑tune on trash dataset  
5. 🧾 Predict class  
6. ♻️ Apply recyclability rules

---

## ⚙️ Algorithms & Techniques
- **Vision Transformer (ViT)**  
- **Transfer learning** (reuse pretrained weights)  
- **Fine‑tuning** on our dataset  
- **Rule mapping** from class → recyclability

---

## ▶️ Running (Google Colab)
1. Open notebook in Colab  
2. Mount Google Drive  
3. Run all cells  
4. Upload image  
5. View predictions 👍

> Works best with GPU runtime (Runtime → Change runtime type → GPU)

---

## 🚀 Future Improvements
- 🔎 Add object detection (multiple items per image)
- 🗂️ Train on a larger dataset
- 📱 Mobile / web deployment
- 🖼 Explainable AI heatmaps
- ⚡ Real‑time classification support

---

## 📜 License
This project is intended for **educational use**.

---

## 🖼 Demo (Screenshots)
_Add output screenshots here when available._

---

Thanks for checking out the project! Contributions, suggestions, and feedback are always welcome 🙌

