```markdown
# 🏠 Karachi House Price Predictor

Welcome to the **Karachi House Price Predictor**, a machine learning web application built using **Streamlit** that estimates house prices in Karachi based on:

- 📍 Location  
- 📐 Total area (in sqft)  
- 🛁 Number of bathrooms  
- 🛏️ Number of bedrooms (BHK)

This tool uses a trained Linear Regression model with location-based one-hot encoding and standardized numerical features.

---

## 🚀 Live Demo

🌐 **Hosted on Streamlit Cloud**  
👉 [Click here to view the live app](https://share.streamlit.io/hammadshah18/Karachi-House-Predictor/master/app.py) *(replace with actual deployed URL)*

---



---

## 🛠 Features

- Streamlit web interface
- Location-based predictions using OneHotEncoding
- Clean UI with background image
- Model trained using Scikit-learn pipeline with preprocessing
- Realtime predictions with user inputs

---

## 📁 Project Structure

```

Karachi-House-Predictor/
├── app.py                      # Streamlit application
├── bg.jpg                      # Background image
├── LinearRegressionModel.pkl   # Trained ML model
├── KarachiHouseCleanData.csv   # Cleaned housing dataset
├── requirements.txt            # Python dependencies

````

---

## 💡 How to Run Locally

### 🧩 1. Clone the Repository

```bash
git clone https://github.com/hammadshah18/Karachi-House-Predictor.git
cd Karachi-House-Predictor
````

### 📦 2. Create Virtual Environment (optional but recommended)

```bash
python -m venv myenv
myenv\Scripts\activate  # Windows
# OR
source myenv/bin/activate  # macOS/Linux
```

### 🔧 3. Install Requirements

```bash
pip install -r requirements.txt
```

### ▶️ 4. Run the App

```bash
streamlit run app.py
```

---

## 🔍 Model Details

* **Algorithm**: Linear Regression
* **Libraries**: `scikit-learn`, `pandas`, `numpy`, `joblib`
* **Preprocessing**:

  * OneHotEncoder for `location`
  * StandardScaler for numerical features

---

## 🙋‍♂️ Author

**Muhammad Hammad**
📧 `hammadshah18@gmail.com`
🎓 B.E. Computer Systems Engineering
🏫 Mehran University of Engineering and Technology, Jamshoro
📍 Tando Adam, Sindh, Pakistan

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

````


