# MachineLearningGroup03
Here are the 3 notebooks of our final delivery.

Steps:
Clone the repository:

Install dependencies: This project requires specific libraries like rapidfuzz and scikit-learn.

Execution Order:

Run Group_03_notebook_untilmodels.ipynb first to see the analysis.

Run modelos_nofunctions.ipynb to generate predictions.

📊 Data Source
The dataset contains information regarding car attributes (brand, engine, year, etc.) and their selling prices. (Note: If this data is from a specific Kaggle competition or a public URL, paste the link here).

📈 Results & Methodology
We utilized a blending strategy of tree-based models. The final model weights used for the submission were:

Histogram Gradient Boosting

Extra Trees

Random Forest

This approach allowed us to balance the variance and bias of the individual models to minimize the Mean Absolute Error (MAE).
