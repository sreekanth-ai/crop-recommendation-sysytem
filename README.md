# 🌾 Crop Recommendation System Using Machine Learning

<img width="577" height="564" alt="image" src="https://github.com/user-attachments/assets/38165ae6-c5b4-4188-b868-52e14a0076e2" />


## 📌 Project Description
This project develops a **machine learning-based system** to recommend the most suitable crop for a farmer based on **soil, weather, and environmental parameters**.  
The system helps farmers make data-driven decisions to maximize yield and optimize resources.  
It is deployed as an interactive **Streamlit app** for real-time recommendations.

---

## 🚀 Key Features
- Input parameters: Soil Nitrogen (N), Phosphorus (P), Potassium (K), pH, Rainfall, Temperature, Humidity  
- Preprocessing: Scaling and cleaning of input features  
- Machine Learning Models: Trained classifiers such as **Random Forest**, **Decision Tree**, or **Gradient Boosting**  
- Real-time Recommendations: Streamlit app predicts the most suitable crop for given input conditions  

---

## 🛠 Tech Stack
- Python  
- pandas, numpy  
- scikit-learn  
- Streamlit  
- Pickle (for saving trained model)

---

## 📂 Project Structure
- `Crop_Recommendation.ipynb` → Jupyter notebook for data exploration, preprocessing, and model training  
- `app.py` → Streamlit app for deployment  
- `model.pkl` → Trained ML model  
- `scaler.pkl` → Preprocessing scaler (if used)

---


## 🖥️ Usage
### Launch the App
```bash
streamlit run app.py
