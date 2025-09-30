# 🌾 Crop Recommendation System Using Machine Learning

<img width="1314" height="541" alt="image" src="https://github.com/user-attachments/assets/ceb902ea-de6e-4324-898a-6afb6b9e4676" />


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
| File | Description |
|------|-------------|
| `Crop Recommendation System.ipynb` | Notebook for data exploration, preprocessing, and model training |
| `Crop_recommendation.csv` | Dataset used for training the model |
| `app.py` | Streamlit app for deployment |
| `crop_recommendation_model.pkl` | Pickled trained ML model |
| `img.jpg` | Image used for app interface or demo |
| `index.html` | Optional HTML file for demo or documentation |
| `README.md` | Project documentation |



## 🖥️ Usage
### Launch the App
```bash
streamlit run app.py
