# WHO CVD Risk Calculator (Non-Laboratory, South Asia – 2023)

This project estimates 10-year cardiovascular disease (CVD) risk based on the **WHO 2023 Non-Laboratory Risk Charts** for the **South Asia region**.  
It uses patient demographic and clinical information (age, sex, systolic blood pressure, BMI, smoking status) to estimate risk levels and categorize them into WHO-defined risk groups.

---

## 🔬 Background

Cardiovascular disease remains one of the leading causes of mortality in South Asia.  
The WHO provides non-laboratory risk charts to help clinicians and researchers assess 10-year CVD risk without requiring blood tests.

This Python tool automates the risk estimation process for datasets, making it ideal for:
- Public health research
- Community-level CVD screening projects
- Epidemiological data analysis

---

## ⚙️ How It Works

1. Input an Excel file with at least these columns:
   - `age`
   - `gender`
   - `weight`
   - `height`
   - `bpsystole` (Systolic Blood Pressure)
   - `smoking` (Yes/No)
2. The script:
   - Calculates BMI
   - Determines risk percentage from WHO tables
   - Categorizes the risk level
3. Outputs an Excel file with:
   - `bmi`
   - `crp_new` (CVD risk %)
   - `crp_new_class` (risk category)

---

## 🚀 How to Run

```bash
# Clone repository
git clone https://github.com/Sangenis11/who-cvd-risk-calculator.git
cd who-cvd-risk-calculator

# Install dependencies
pip install -r requirements.txt

# Run the script
python who_cvd_risk_nonlab_south_asia.py

---

## 🧩 Adaptability

This calculator currently supports the South Asia WHO 2023 non-laboratory risk chart.
However, it can be easily updated to adapt for other WHO regions (e.g., Africa, Europe, Western Pacific, the Americas) by modifying the lookup parameters and thresholds according to the respective regional charts.

Planned future updates:

🌍 Global regional support

💻 Interactive dashboard

---

## 📚 Citation

If you use this project, please cite:
World Health Organization (2023). WHO CVD Risk Charts – Non-Laboratory Version.

---

## 👨‍💻 Author & Contact

Sangenis Ayao Assogba
Biostatistician | Epidemiologist | Health Data Scientist

📍 West Africa (Togo) | 🇮🇳 Based in India
📧 Sangenisassogba1@gmail.com

---
