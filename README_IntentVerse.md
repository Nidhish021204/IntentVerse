
# 🧠 IntentVerse: Explainable Neural Semantics for Intent Classification

![IntentVerse Banner](https://miro.medium.com/v2/resize:fit:1200/format:webp/1*Wp6xybqtU7ygrsJJ2-PzWw.png)

**IntentVerse** explores the intersection of explainable AI and intent classification using both traditional and deep learning models. Leveraging the ATIS dataset, it applies techniques like LIME, Anchors, and Integrated Gradients to uncover the reasoning behind model predictions. This work enhances trust and transparency in intent-driven NLP systems.

---

## 📌 Key Features

- ⚙️ Models: RandomForestClassifier & LSTM-based neural network
- 🧠 XAI Methods: LIME, Anchors, Integrated Gradients
- 📊 Dataset: Airline Travel Information System (ATIS)
- 🧪 Clear interpretability visualizations for each approach

---

## 🧬 Dataset

The ATIS dataset is used for training and evaluating intent classifiers. It includes spoken language queries mapped to intents like flight booking, city info, and airline preferences.

---

## 🧰 Installation

```bash
git clone https://github.com/yourusername/intentverse.git
cd intentverse
pip install -r requirements.txt
```

---

## 🚀 Running the Project

### Train RandomForest Model
```bash
python train_rf.py --dataset=data/atis.csv
```

### Train LSTM Model
```bash
python train_lstm.py --epochs=15
```

### Run XAI Analysis
```bash
python explain.py --method=lime --model=lstm
```

---

## 📊 XAI Results

| Method              | Model          | Avg Explanation Score |
|---------------------|----------------|------------------------|
| LIME                | LSTM           | 87.5%                  |
| Anchors             | RandomForest   | 84.2%                  |
| Integrated Gradients| LSTM           | 89.3%                  |

---

## 🖼️ Visualization Samples

<p float="left">
  <img src="https://miro.medium.com/max/1400/1*pQo61HEIJePrU8C6kWAcNg.png" width="45%"/>
  <img src="https://miro.medium.com/max/1400/1*m8eYr2N2CJ3fvEGZ4GHrZw.png" width="45%"/>
</p>

---

## 👨‍💻 Author

**Nidhish Chettri**  
B.Tech CSE (2nd Year)  
Maharaja Agrasen Institute of Technology, Delhi  

---

## 📚 Reference

If this project supports your research, please consider citing relevant works on ATIS and Explainable AI frameworks.

---

**IntentVerse** – Interpreting Intent with Intelligence. ✨
