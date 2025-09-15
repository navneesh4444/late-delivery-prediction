# 🚚 Late Delivery Prediction

This project predicts whether a shipment will be **late or on time** using machine learning.  
It helps identify risky orders and routes so logistics teams can **take action before delays happen**.

---

## 🔍 Overview
- Trained a **HistGradientBoostingClassifier** model  
- **Input features:**  
  - Units  
  - Weight  
  - Distance  
  - Material Handling  
- **Outputs:**  
  - `predicted_late_order` (True/False)  
  - `late_probability` (confidence score)  
  - Risk Band (Low / Medium / High)  

---

## 🛠️ Tools Used
- **Python:** Pandas, NumPy, Scikit-learn  
- **Visualization:** Matplotlib, Seaborn, Folium  
- **Jupyter Notebook** for experimentation  

---

## 📈 Model Performance
- Evaluated with **Accuracy, Precision, Recall, F1, ROC-AUC**  
- Visualized using **ROC Curve** and **Precision–Recall Curve**  

---

## 📊 Insights
- Very **small** and **very large** shipments are more prone to delays  
- Long-distance shipments increase late delivery probability  
- Risk bands help focus on the **most critical orders**  

---

## 🌍 Route Risk Map
Interactive map of routes (origin → customer):  
- 🟢 Green → Low risk  
- 🟠 Orange → Medium risk  
- 🔴 Red → High risk  

Example output:  
*(Map is also available as `route_risk_map.html` for interactive exploration.)*

---

## 📊 Sample Output
| Units | Weight | Distance | Predicted Late | Late Probability | Risk Band |
|-------|--------|----------|----------------|-----------------|-----------|
| 580   | 1500   | 1000     | False          | 0.177           | Low Risk  |
| 430   | 900    | 500      | False          | 0.147           | Low Risk  |

---

## 🙌 Author
**Navneesh Goyal**  
Final-year B.Tech, Industrial & Production Engineering @ NIT Jalandhar  
**LinkedIn:** [Navneesh Goyal](https://www.linkedin.com/in/navneesh-goyal/)  
📧 navneeshg.4444@gmail.com
