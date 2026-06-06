**Readme · MD**
🛡️ Cyber Attacks Data Analysis
An exploratory data analysis (EDA) project examining patterns in global cyber attacks — breaking down attack frequency by year, industry, motive, and location using Python visualisations.

📓 Notebook
File	Description
Data_of_cyber_attacks.ipynb	Main analysis notebook — data loading, cleaning, and visualisations
📊 Dataset — all_recs.xlsx
The dataset contains records of cyber attacks with the following key columns:

Column	Description
Year	The year the attack occurred
Location	Country or region where the attack took place
Motive	Reason behind the attack (e.g. financial, political, espionage)
Industry	Sector targeted (e.g. finance, healthcare, government)
📈 Visualisations
The notebook produces four main charts, all built with Seaborn and Matplotlib:

1. 📅 Attack Frequency by Year
Horizontal bar chart showing how the number of recorded attacks has changed over time — useful for spotting surges in activity across different periods.

2. 🏭 Attack Frequency by Industry
Shows which sectors are most frequently targeted. Industries are sorted by attack count, highlighting the most vulnerable domains.

3. 🎯 Attack Frequency by Motive
Breaks down the intent behind attacks — whether financial gain, political disruption, espionage, or other factors drive cyber threats.

4. 🌍 Attack Frequency by Location
A tall horizontal chart ranking countries/regions by number of recorded attacks, giving a geographic view of the global threat landscape.

🛠️ Tech Stack
Library	Purpose
pandas	Data loading and manipulation
numpy	Numerical operations
matplotlib	Base plotting
seaborn	Statistical visualisations
🚀 Getting Started
1. Clone the repo
bash
git clone https://github.com/your-username/cyber-attacks-dataset.git
cd cyber-attacks-dataset
2. Install dependencies
bash
pip install pandas numpy matplotlib seaborn openpyxl
3. Add the dataset
Place all_recs.xlsx in the project directory (or update the file path in the notebook to match where you saved it).

4. Run the notebook
bash
jupyter notebook Data_of_cyber_attacks.ipynb
⚠️ Disclaimer
This project is for educational and analytical purposes only. All data reflects publicly available or aggregated records of cyber incidents.

📄 License
MIT License

