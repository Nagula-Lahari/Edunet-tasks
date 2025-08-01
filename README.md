# 🚜 Farm Irrigation System using Machine Learning

This project uses sensor data to intelligently predict irrigation needs for multiple farm parcels using machine learning. It includes data cleaning, model training, evaluation, visualization, and exports.

---

## 📁 Dataset

- **File:** `irrigation_machine.csv`
- **Features:** 20 sensor columns (`sensor_0` to `sensor_19`)
- **Targets:** 3 parcel columns (`parcel_0`, `parcel_1`, `parcel_2`)

---

## 🔧 Features

- ✅ Data cleaning (removal of unused columns)
- ✅ Feature scaling using `StandardScaler`
- ✅ Multi-label classification using `MultiOutputClassifier` with `DecisionTreeClassifier`
- ✅ Evaluation: Accuracy, Precision, Recall
- ✅ Confusion matrix heatmaps for each target
- ✅ Correlation heatmap between sensors and parcel outputs
- ✅ Feature importance bar plots
- ✅ Model export as `.pkl` files
- ✅ Predictions saved as `.csv`

---

## 📊 Outputs

| File                        | Description                        |
|-----------------------------|------------------------------------|
| `Irrigation_Model.pkl`      | Trained ML model                   |
| `Scaler.pkl`                | Scaler used for feature scaling    |
| `Irrigation_Predictions.csv`| Predictions on test data           |
| `irrigation_machine.csv`    | Input dataset                      |

---

## 🚀 How to Run

1. Clone the repo or download the files.
2. Place `irrigation_machine.csv` in the same folder.
3. Run the Jupyter Notebook or Python script.
4. Run the app.py file by using the command ( streamlit run app.py )
5. copy / ctrl+click the url and open it in any web browser 
6. View results and visualizations.

---

## 🧠 Model Used

- `MultiOutputClassifier` with `DecisionTreeClassifier`
- Handles multi-label outputs (`parcel_0`, `parcel_1`, `parcel_2`) simultaneously

---

## 📈 Visualizations

- Confusion matrices
- Correlation heatmap
- Feature importance bar chart

---

## 🔮 Future Improvements

- Add Streamlit web UI for predictions
- Integrate weather data
- Deploy as REST API using Flask or FastAPI
- Hyperparameter tuning with GridSearchCV

---

## 👩‍💻 Author

- **Nagula Lahari** – B.Tech CSE, 3rd Year  
- Project as part of internship

---

## 📄 License

This project is for educational and research purposes only.

