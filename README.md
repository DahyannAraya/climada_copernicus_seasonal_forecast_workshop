<img src="images/Logos.png" alt="Project Logos" width="70%"/>

# **Copernicus Seasonal Forecast Module** 

<img src="images/repo_qr.png" alt="Repository QR Code" width="150"/>

This repository contains a **Jupyter Notebook** that showcases the functionalities of the new **seasonal forecast module** of [CLIMADA](https://climada.ethz.ch/). The module facilitates the management of **seasonal forecast data** from the [Copernicus Climate Data Store](https://cds.climate.copernicus.eu) (CDS) as part of the [U-CLIMADAPT project](https://www.copernicus-user-uptake.eu/user-uptake/details/responding-to-the-impact-of-climate-change-u-climadapt-488). 
This module provides comprehensive tools for downloading, processing, and computing climate indices, as well as generating hazard objects based on seasonal forecast datasets, particularly [Seasonal forecast daily and subdaily data on single levels](https://cds.climate.copernicus.eu/datasets/seasonal-original-single-levels?tab=overview). 
Designed for seamless integration with the [CLIMADA](https://climada.ethz.ch/) (CLIMate ADAptation) platform, this module supports climate risk assessment and facilitates the development of effective adaptation strategies.


## **Features**
- 📥 **Download** seasonal forecast data from CDS.
- 🔄 **Process** raw seasonal forecast datasets.
- 📊 **Compute climate indices** for analysis.
- 🌍 **Generate hazard objects** for climate risk assessment.
- 🛠️ **Integration with [CLIMADA](https://climada.ethz.ch/)** (CLIMate ADAptation) for climate impact modeling.

## **Requirements**
Before running the notebook locally, ensure you have the following dependencies installed:

- `climada`
- `climada_petals`
- `cdsapi`
- `numpy`
- `pandas`
- `matplotlib`

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
