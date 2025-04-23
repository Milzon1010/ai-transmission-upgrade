# AI for Transmission Capacity Upgrade Prediction

This is a prototype AI project that predicts whether a fiber or microwave link requires a capacity upgrade.  
It is based on historical network KPI data such as traffic utilization, BER, latency, jitter, and downtime.

---

## 📌 Features
- Uses a realistic dummy dataset of 500 site links (Microwave & Fiber)
- KPI-based threshold labeling (Upgrade Needed or Not)
- Random Forest classifier for binary prediction
- Visual analysis: traffic distribution, latency by label, feature importance
- Designed as a showcase project for telecom + AI career shift

---

## 📁 Files Included
| File | Description |
|------|-------------|
| `ai_transmission_upgrade.ipynb` | Main Jupyter Notebook with all code, charts, and model |
| `link_kpi_data_dummy.csv` | Simulated KPI dataset |
| `README.md` | This documentation |

---

## ⚙️ Tech Stack
- Python 3.11
- Jupyter Notebook (VS Code or Colab)
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

---

## 💡 Use Case
> For telecom engineers and analysts to assess link health and forecast capacity requirements.  
> Can be scaled to real operator datasets or integrated into dashboard tools.

---

## 📈 Sample Visual Output

- Traffic Utilization Histogram
- Latency Boxplot (Upgrade vs Non-upgrade)
- Confusion Matrix & Classification Report
- Feature Importance Bar Chart

---

## 📞 Author
**Muhammad Milzon**  
🌐 [LinkedIn](https://linkedin.com/in/milzon)  
✉️ milzon.ltf@gmail.com

---
