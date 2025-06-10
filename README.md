# 🌬️ Wind Energy Investment Analysis for Wow Energy

This project was created for **Wow Energy**, a company exploring potential investment opportunities in U.S. wind energy infrastructure. The analysis identifies promising states based on wind capacity and recommends suitable partner types and companies.

---

## 📊 Objective

To support strategic investment decisions by:
- Analyzing wind turbine installation data across the U.S.
- Categorizing states by capacity levels (high, medium, low)
- Recommending investment partners based on state capacity
- Identifying real-world U.S. companies aligned with investment goals
- Providing clear visualizations and business-friendly insights

---

## 📁 Data Sources

- `Wind_Energy_Investment_Partners.csv`  
  Contains descriptions and investment characteristics of different partner types.

- `wind_turbine_20220114.csv`  
  Dataset with details of over 70,000 wind turbines in the U.S., including location, capacity, height, manufacturer, and commissioning year.

---

## 🧪 Analysis Overview

- Cleaned and standardized partner and turbine data
- Grouped turbine capacity by state
- Defined capacity tiers using quantiles
- Mapped recommended partner types per tier
- Identified key potential companies for collaboration
- Created informative visualizations

---

## 📈 Key Visualizations

- 📌 Top 10 U.S. States by Installed Wind Capacity
- 📈 Wind Turbine Installations Over Time
- 🔧 Turbine Capacity Distribution
- 🗺️ State Capacity Tier Categorization
- 🏢 Partner Capacity Comparison (GW)

All plots are saved as `.png` and can be found in the `plots/` folder.

---

## 🧠 Recommendations

| Capacity Tier | Example States      | Recommended Partners                                     |
|---------------|---------------------|-----------------------------------------------------------|
| High          | TX, IA, OK, CA, KS  | Utility Companies, Private Equity Firms                   |
| Medium        | AZ, ID, MO, NY      | Government Agencies, Green Energy Funds                   |
| Low           | AK, CT, FL, RI      | Community Investment, Individual Investors                |

### 🔎 Potential U.S. Partners
- **NextEra Energy** – Largest wind operator in the U.S.
- **Duke Energy** – Expanding renewables with strong capital
- **AES Corporation** – Flexible financing and wind + storage
- **Brookfield Renewable** – Global wind asset leader
- **BlackRock REI** – Institutional investor in multi-GW assets

---

## 💡 Tools Used

- Python (pandas, matplotlib, seaborn)
- Jupyter Notebooks
- PowerPoint (for presentation)
- Data visualization & business intelligence techniques

---

## 🧾 License

This project is provided for educational and analytical purposes. Attribution required if reused or shared.

---

## 🙌 Acknowledgements

Thanks to Wow Energy for the problem statement and the wind energy community for accessible open datasets.
