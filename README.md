# CarbonCostCalc
![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey)

**CarbonCostCalc** is a modular Python-based software add-on designed to integrate carbon pricing mechanisms into oilfield feasibility models built in Microsoft Excel. It allows analysts to simulate the impact of carbon taxes or cap-and-trade schemes on IRR, NPV, and breakeven pricing.

---

## 🔧 Features

- Excel plugin using `xlwings`
- Carbon pricing from live ETS APIs or static pricing inputs
- Emission factor–based cash flow adjustments
- Recalculation of IRR and NPV with carbon liabilities
- Scenario analysis and volatility modeling for long-term projects

---

## 🖥️ Included Files

### `src/` folder:
- `carbon_price_fetcher.py`: API integration to fetch real-time carbon prices
- `impact_model.py`: Adjusts financials for emissions-based liabilities
- `xl_adapter.py`: Connects Python models with Excel UI
- `config_loader.py`: Loads region-specific emission factors and tax logic

### `examples/` folder:
- `sample_model.xlsx`: Demo Excel sheet with IRR calculation
- `usage_demo.py`: Sample usage of the full workflow

### Other files:
- `requirements.txt`: List of required Python libraries
- `LICENSE`: MIT License
- `README.md`: Project overview and usage guide

---

## ⚙️ Installation

To install dependencies, run:

```bash
pip install xlwings requests pandas

## 📊 Use Case Article

This repository supports the software described in the research article:  
**"CarbonCostCalc: A Software Add-On for Integrating Carbon Pricing into Oil Project Feasibility Models"**  
(submitted to *Software Impacts* – Elsevier Q1 Journal)

## 📜 License

This project is licensed under the [MIT License](LICENSE).

## 📫 Contact

For issues, questions, or feature requests, please contact:  
📧 **sampath.evs@gmail.com**

