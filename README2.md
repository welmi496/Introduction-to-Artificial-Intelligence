# Image Classification Assignment

This project contains a Google Colab notebook for image classification using a Random Forest Classifier with GridSearchCV, along with an SVM comparison.

## Dataset
The dataset is an image dataset organized into five classes:
- dalmatian
- dollar_bill
- pizza
- soccer_ball
- sunflower

Total images: 309

## Files Included
- `Assignment.ipynb` - Main Google Colab notebook
- `report_image_classification.pdf` - 2-page report
- `model_comparison.csv` - Evaluation summary
- `images.zip` - Dataset ZIP file used in the notebook

## How to Run in Google Colab
1. Upload `images.zip` to your Colab session or Google Drive.
2. Open `Assignment.ipynb` in Google Colab.
3. Make sure the `ZIP_PATH` variable points to your dataset ZIP file.
4. Run all cells from top to bottom.

## Methods Used
- Image resizing to 16x16
- Pixel normalization
- Train-test split
- Random Forest with GridSearchCV
- Evaluation using accuracy, precision, recall, F1-score, confusion matrix, and classification report
- Feature importance visualization
- Prediction on a new image
- SVM comparison

## Results Summary
- Random Forest Accuracy: 0.7097
- SVM Accuracy: 0.7097
