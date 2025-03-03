# **Copernicus Seasonal Forecast Module**

This repository contains a **Jupyter Notebook** that demonstrates how to manage **seasonal forecast data** from the [Copernicus Climate Data Store (CDS)](https://cds.climate.copernicus.eu) as part of the **U-CLIMADAPT project**. It provides tools for downloading, processing, and computing climate indices to generate hazard objects for **seasonal forecast risk assessment**.

## **Features**
- 📥 **Download** seasonal forecast data from CDS.
- 🔄 **Process** raw seasonal forecast datasets.
- 📊 **Compute climate indices** for analysis.
- 🌍 **Generate hazard objects** for climate risk assessment.
- 🛠️ **Integration with [CLIMADA](https://climada.ethz.ch/)** (CLIMate ADAptation) for climate impact modeling.

## **Requirements**
Before running the notebook, ensure you have the following dependencies installed:

```bash
pip install climada climada_petals cdsapi numpy pandas matplotlib
```

## **Usage**

<a target="_blank" href="https://colab.research.google.com/github/DahyannAraya/climada_copernicus_seasonal_forecast_workshop/blob/main/climada_copernicus_seasonal_forecast_workshop.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

1. Clone the repository:
   ```bash
   git clone https://github.com/DahyannAraya/climada_copernicus_seasonal_forecast_workshop.git
   cd climada_copernicus_seasonal_forecast_workshop
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook climada_copernicus_seasonal_forecast_workshop.ipynb
   ```
3. Follow the notebook instructions to download and process **seasonal forecast data**.

## **References**
- [Copernicus Climate Data Store](https://cds.climate.copernicus.eu)
- [CLIMADA Documentation](https://climada.ethz.ch/)
- [U-CLIMADAPT Project](https://www.copernicus-user-uptake.eu/user-uptake/details/responding-to-the-impact-of-climate-change-u-climadapt-488)
