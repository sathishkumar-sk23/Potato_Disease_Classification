# Potato Disease Classification

This repository contains a deep learning model for classifying potato diseases using image data. The model was trained on a dataset containing images of healthy and diseased potato leaves, achieving an accuracy of **95%**.

## Project Structure

- `PotatoDiseasesClassifier_Experiments.ipynb` → Contains different models and approaches tested.
- `PotatoDiseasesClassifier_Final.ipynb` → The selected model with testing and final evaluation.
- `requirements.txt` → List of dependencies required to run the project.
- `model/` → Trained model weights.

## Dataset Details
- **Classes:**
  - Potato___Healthy
  - Potato___Early_Blight
  - Potato___Late_Blight
- The dataset was split into **80% training** and **20% testing**.
- Kaggle Dataset Link: https://www.kaggle.com/datasets/hafiznouman786/potato-plant-diseases-data/data

##  Model Training Process
1. **Get Data**: Load the dataset and create train-test splits.
2. **Visualize Images**: Display sample images to understand data distribution.
3. **Transform Data**: Apply data augmentation and normalization.
4. **Load Images**: Use PyTorch `DataLoader` for efficient batch processing.
5. **Train Model**: Experimented with multiple CNN architectures.
6. **Make Predictions**: Evaluate the model on test data.
7. **Evaluate Performance**: Compute accuracy, confusion matrix, and loss curves.
8. **Predict Custom Images**: Test the model on new images.
9. **Save Model**: Store trained weights for future use.

## 🛠️ Installation & Usage
### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 2️⃣ Run Jupyter Notebook
```bash
jupyter notebook
```

### 3️⃣ Load and Train Model
Open `PotatoDiseasesClassifier_Final.ipynb` and execute the cells to train/evaluate the model.

### 4️⃣ Predict on New Images
You can test the model with new potato leaf images by running the **Predict Custom Image** section in the final notebook.

##  Results
- The best-performing model achieved **95% accuracy** on the test set.
- The confusion matrix shows strong classification performance across all three categories.

---

