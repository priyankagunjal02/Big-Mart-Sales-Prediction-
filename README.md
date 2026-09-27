# Big Mart Sales Prediction

## Project Overview
This project predicts Big Mart product sales using machine learning. The provided `Train.csv` dataset is used to train and evaluate an XGBoost regression model.

## Dataset
The internship-provided datasets are:
- `Train.csv` — 8,523 rows and 12 columns
- `Test.csv` — 5,681 rows and 11 columns

The notebook uses `Train.csv` for the modeling workflow. It splits the data into training and validation/test portions using an 80:20 split with `random_state=2`. `Test.csv` is retained as the provided dataset for the project.

## Model
- **Algorithm:** XGBoost Regressor
- **Library:** XGBoost
- **Evaluation metric:** R² (R Squared)

## Results
The model was run successfully in Google Colab.

| Dataset | R² Score |
|---|---:|
| Training | 0.8751 |
| Testing | 0.5156 |

The exact notebook outputs were:
- Training R² = `0.8750519939334624`
- Testing R² = `0.5155979721907443`

## Project Files
- `Big_Mart_Sales_Prediction.ipynb` — Google Colab/Jupyter Notebook
- `Train.csv` — training dataset
- `Test.csv` — provided test dataset
- `README.md` — project documentation
- `requirements.txt` — required Python libraries
- `Big Mart Sales Prediction.pptx` — project presentation

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Google Colab
- Jupyter Notebook

## How to Run
1. Open `Big_Mart_Sales_Prediction.ipynb` in Google Colab or Jupyter Notebook.
2. Upload `Train.csv` to the notebook environment.
3. Run the notebook cells from top to bottom.
4. The notebook trains the XGBoost regression model and prints the R² scores.

## Project Objective
The objective is to build a regression model for predicting Big Mart sales and evaluate the model using the R² score.

## Author
Internship Project — Big Mart Sales Prediction
