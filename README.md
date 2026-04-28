
# Titanic ML Classifier 🚢

Predicting passenger survival using Machine Learning (Random Forest, KNN, Logistic Regression).

## Results
| Model | Accuracy |
|-------|----------|
| Random Forest | **83.8%** |
| Logistic Regression | 79.9% |
| KNN | 71.5% |

## Features Used
- Passenger class, Sex, Age, Fare
- Family Size (engineered), Is Alone (engineered)
- Embarked port

## Key Findings
- **Sex** is the most important feature — females survived at much higher rates
- **1st class** passengers had significantly better survival odds
- Single male passengers in 3rd class: 92% chance of not surviving

## Tech Stack
Python | Scikit-learn | Pandas | NumPy | Matplotlib | Seaborn

## How to Run
```bash
pip install -r requirements.txt
jupyter lab
```
Open `notebook.ipynb` and run all cells.