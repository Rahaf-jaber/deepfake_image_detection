# Deepfake Image Detection

CNN-based binary classifier to distinguish **real vs. deepfake** facial images using a labeled Kaggle dataset.

## Highlights
- 🧠 Convolutional Neural Network (CNN) with transfer-friendly training loop
- 🧹 Clean pipeline: preprocessing → train → evaluate → visualize
- 📊 Test accuracy: **~88%**; precision/recall/F1 **> 0.85** 

## Running the Script
- Open deepfake_detector.ipynb in Colab.
- Update dataset paths.
- Run all cells to train, evaluate, and save plots.

## Results
- Accuracy: ~88% on test set
- Metrics: precision/recall/F1 all > 0.85
- Validation: confusion matrix + visual predictions

## Notes
- Dataset: Kaggle (real & fake faces)
- Optimizer: Adam, Loss: Binary Crossentropy
