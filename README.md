
# 🚦 Traffic Accident Prediction with Decision Trees and SHAP

This project uses a Decision Tree classifier to predict the likelihood of a traffic accident based on various real-world features like weather, road type, driver behavior, and vehicle information. In addition to training the model, it emphasizes **explainability** using **SHAP (SHapley Additive Explanations)** to understand which features influence predictions the most.

## 📁 Project Structure

- `dataset_traffic_accident_prediction1.csv` — Main dataset
- `Untitled.ipynb` — Core Jupyter notebook with code, training, and visualization
- `report.docx` — Word document tutorial report with results, visualizations, and explanation
- `images/` — Folder containing all figures used in the report

## 🔍 Key Features

- 📊 **Exploratory Data Analysis (EDA)** to understand distributions and relationships
- 🧼 **Data cleaning and preprocessing** including missing value handling and encoding
- 🌲 **Decision Tree Classifier** with visual explanation of tree structure
- 📉 **Model evaluation** using confusion matrix and accuracy over depth
- 🔍 **SHAP explainability** to highlight global and local feature importance

## 🛠️ Requirements

- Python 3.9+
- pandas
- numpy
- scikit-learn
- shap
- matplotlib
- seaborn

Install dependencies using:

```bash
pip install -r requirements.txt
```

## 🧠 Key Learnings

- How Decision Trees offer built-in transparency
- How to handle real-world structured data
- How to apply SHAP to enhance model interpretation
- Why explainability matters in safety-critical applications like traffic prediction

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgements

- [SHAP by Scott Lundberg](https://github.com/slundberg/shap)
- [Scikit-learn](https://scikit-learn.org/)
- UK Department for Transport (for domain inspiration)

