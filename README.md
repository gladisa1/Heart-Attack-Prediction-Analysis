## Code

### Project Structure

The project code is organized into the following directories and files:

- `notebooks/`: Contains Jupyter notebooks for data analysis, preprocessing, and model development.
- `src/`: Includes Python scripts for utility functions and data processing.
- `data/`: Holds the dataset used in the project.

### Dependencies

Make sure to install the required dependencies before running the code:

```bash
pip install -r requirements.txt
The requirements.txt file lists all necessary Python packages and their versions.

How to Run
Navigate to the notebooks/ directory.
Open the Jupyter notebooks in your preferred environment (e.g., Google Colab).
Execute the code cells sequentially.
Ensure the dataset is available in the data/ directory, and any required preprocessing steps are performed.

Note on Reproducibility
To reproduce the exact environment used in this project, consider setting up a virtual environment or container based on the provided requirements.txt file.

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt

This ensures consistent dependencies across different environments.

Model Evaluation
Metrics such as accuracy, precision, recall, and F1 score were used to evaluate the performance of the machine learning models.

# Example code snippet for model evaluation
from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score

# Assuming y_true and y_pred are your true and predicted labels
accuracy = accuracy_score(y_true, y_pred)
precision = precision_score(y_true, y_pred)
recall = recall_score(y_true, y_pred)
f1 = f1_score(y_true, y_pred)

print(f"Accuracy: {accuracy}, Precision: {precision}, Recall: {recall}, F1 Score: {f1}")
