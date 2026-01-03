# Demand Forecasting Excel Model

This repository contains a lightweight Excel-based demand forecasting model designed to compare multiple forecasting methods and explicitly track forecast error.

The purpose of this model is to make common forecasting logic **transparent and inspectable**, rather than hidden behind software interfaces or black-box tools.

It is not intended to replace an ERP or advanced forecasting system, but to clarify how such systems estimate demand and evaluate forecast performance under the hood.

---

## Purpose

The model is intended to support understanding and discussion of forecasting behavior by illustrating how different approaches perform under real-world demand variability.

It emphasizes transparency, interpretability, and traceability of calculations over algorithmic sophistication.

---

## What the model includes

The workbook provides:

- Multiple demand forecasting methods
- Explicit forecast error calculation and comparison
- Clear separation between:
  - Input data
  - Forecast outputs
  - Error metrics
- A reference sheet explaining assumptions, formulas, and methodology

---

## Intended use

This model is intended for:

- Educational purposes
- Scenario analysis
- Comparing forecasting approaches
- Explaining forecasting and error-measurement logic
- Supporting planning and process discussions

It is not intended to replace an ERP system, forecasting platform, or automated planning tool. Most production systems perform these calculations internally; this model exists to make those calculations visible and understandable.

---

## Limitations

- The model is not automated or optimized for large-scale production use.
- Results depend on the quality and representativeness of historical demand data.
- External drivers such as promotions, policy changes, or supply disruptions are not explicitly modeled.
- The model assumes stable demand-generating processes over the historical window.

---

## Related work

This project complements an inventory planning model that translates demand uncertainty into inventory policy decisions.
