# CarbonCostCalc

**CarbonCostCalc** is a modular Python-based software add-on designed to integrate carbon pricing mechanisms into oilfield feasibility models built in Microsoft Excel. It allows analysts to simulate the impact of carbon taxes or cap-and-trade schemes on IRR, NPV, and breakeven pricing.

---

## 🔧 Features

- Excel plugin using `xlwings`
- Carbon pricing from live ETS APIs or custom inputs
- Emission factor-based cost adjustment
- Financial recalculations (IRR, NPV) with carbon liabilities
- Scenario testing and volatility modeling

---

## 🖥️ Demo Files

- `sample_model.xlsx` – Excel model with carbon pricing plugin
- `impact_model.py` – Main financial logic
- `carbon_price_fetcher.py` – ETS API integration
- `xl_adapter.py` – Excel-Python bridge
- `config_loader.py` – Region-specific config support

---

## 📦 Requirements

```bash
pip install xlwings requests pandas
