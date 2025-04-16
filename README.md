# Mushroom-competition
## 🍄 Mushroom Classification - Predicting Poisonous Mushrooms

This project was created for a **Kaggle competition** using a mushroom dataset to predict whether a mushroom is **poisonous or edible** based on its physical characteristics.

I applied **Supervised Machine Learning** with a **Random Forest Classifier**, using **OneHotEncoder** for categorical features. To prioritize safety, I implemented a custom `FixedThresholdClassifier` that tuned the decision threshold to avoid **false negatives** — ensuring no poisonous mushrooms are predicted as safe.

---

### 🧑‍🔬 Fictitious Backstory

Each autumn in Catalonia, mushroom hunting is a beloved tradition — but misidentifying mushrooms has led to serious health risks. The Department of Health asked for a model to predict toxicity from basic attributes, helping reduce hospital overload and save lives.

---

### ✅ Results

- **Accuracy:** 94%  
- **Recall:** 1.0 (no false negatives)  
- 🥈 **Placed 2nd** among my bootcamp peers in the competition

