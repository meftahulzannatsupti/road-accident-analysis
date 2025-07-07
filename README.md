# 🚗 Road Accident Analysis & Fatal Injury Prediction

This project explores UK road accident data to predict fatal injuries using machine learning models, while uncovering patterns that inform real-world road safety improvements. It combines Exploratory Data Analysis (EDA), feature engineering, and classification modeling.

---

## 📊 Dataset Overview

The dataset underwent extensive preprocessing:
- **Irrelevant columns removed**
- **Missing values** handled through imputation and removal
- **EDA with Sweetviz** for feature distribution and correlations
- **Categorical encoding** via One-Hot Encoding
- **Numerical normalization** for consistent scaling
- **Class balancing** to prevent model bias

---

## 🤖 Models Used

Two models were developed and compared:
- **Decision Tree Classifier**
- **Random Forest Classifier**

Evaluation was based on:
- Accuracy
- Precision
- Recall
- Confusion Matrix

---

## 💡 Key Insights

- **Accident Timing:** High frequency during morning and late afternoon rush hours.
- **Day of Week:** Thursdays and Fridays show spikes due to increased social activity.
- **Vehicle Type:** Motorcycles with large engine sizes contribute disproportionately to fatalities.
- **Pedestrian Involvement:** Requires targeted safety enhancements.
- **Weather Impact:** Adverse weather significantly increases severity.
- **Speed Zones:** Strong correlation with accident severity.

---

## 🧠 Recommendations

- Launch **safety campaigns** during rush hours and on peak days.
- Promote **motorcycle safety programs** for specific engine sizes and timing.
- Improve **pedestrian safety** through better visibility and infrastructure.
- Raise awareness of **weather-related driving risks**.
- Enforce **speed limits** more strictly in high-risk zones.

---

## 📁 Project Structure

- `road_accident_analysis.ipynb` — Full Jupyter analysis and modeling
- `accident_data.csv` — Sample dataset (if shareable)
- `requirements.txt` — Required Python libraries
- `README.md` — Documentation

---

## 📈 Conclusion

This analysis provides actionable insights into road accident patterns and their contributing factors. The project not only builds predictive models for fatal injuries but also outlines realistic, targeted strategies for accident prevention. Its findings can support policy decisions and awareness programs aimed at reducing road fatalities.

---

## 👤 Author

**Meftahul Zannat**  
MSc Artificial Intelligence & Data Science — University of Hull  
📧 meftahulzannat3598@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/meftahul-zannat-susupti98)  
🔗 [GitHub](https://github.com/meftahulzannatsupti)

---

## 🚀 Future Work

- Apply ensemble techniques like Gradient Boosting
- Deploy model using Streamlit for interactive dashboards
- Add geospatial visualization (e.g., accident map with Folium)


