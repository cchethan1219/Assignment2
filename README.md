##  Approach

1. **Data Preprocessing**
   - Datetime parsing and feature extraction
   - Scaling numeric features
   - Label encoding target classes

2. **EDA**
   - Visualize class balance
   - Distribution of each feature

3. **Modeling**
   - Train/Test split (time-aware: last date as test)
   - Train Random Forest Classifier
   - Evaluate with accuracy, precision, recall, F1-score

4. **Export**
   - Save model (`.pkl`)
   - Save visualizations (`.png`)

---

##  Evaluation Metrics

- Accuracy
- Precision, Recall, F1-Score (per class)
- Confusion Matrix

---

##    How to Run

###  Run via Python


# Run the main script
python main.py
