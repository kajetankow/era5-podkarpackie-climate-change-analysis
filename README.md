# ERA5 Climate Change Analysis for Podkarpackie Voivodeship

## 🇵🇱 Opis projektu

Projekt dotyczy analizy zmian klimatycznych na obszarze województwa podkarpackiego w latach **2005–2025**. Analiza została wykonana na podstawie godzinowych danych reanalizy **ERA5** udostępnianych przez **Copernicus Climate Data Store**.

Dane zostały poddane przetwarzaniu, czyszczeniu oraz agregacji przestrzennej i czasowej do rozdzielczości dziennej, miesięcznej i rocznej. Celem projektu było wykrycie długookresowych trendów klimatycznych, zmian sezonowych oraz wybranych ekstremów pogodowych w regionie.

Analiza obejmuje między innymi temperaturę powietrza, temperaturę punktu rosy, temperaturę powierzchni, opady, pokrywę śnieżną, wilgotność gleby, promieniowanie, parowanie, spływ powierzchniowy oraz wskaźniki związane z bilansem wodnym i energetycznym.

---

## 🇺🇸 Project Description

This project analyzes climate change signals in **Podkarpackie Voivodeship, Poland**, over the period **2005–2025**. The analysis is based on hourly **ERA5 reanalysis data** provided by the **Copernicus Climate Data Store**.

The dataset was processed, cleaned, and aggregated spatially and temporally into daily, monthly, and annual indicators. The goal of the project was to identify long-term climate trends, seasonal changes, and selected weather extremes in the region.

The analysis covers variables such as air temperature, dew point temperature, surface temperature, precipitation, snow cover, soil moisture, radiation, evaporation, runoff, and indicators related to water and energy balance.

---

## Main Workflow

- ERA5 data acquisition from Copernicus Climate Data Store
- Data preprocessing and cleaning
- Spatial aggregation over the Podkarpackie region
- Temporal aggregation into daily, monthly, and annual indicators
- Exploratory Data Analysis
- Climate indicator engineering
- Linear trend modeling
- Statistical significance testing
- Visualization of climate trends and anomalies
- Technical report preparation

---

## Tech Stack

- Python
- pandas
- NumPy
- SciPy
- Matplotlib
- NetCDF / CSV
- Bash
- ERA5 reanalysis data
- Jupyter Notebook

---

## Repository Structure

```text
ERA5-PODKARPACKIE-CLIMATE-CHANGE-ANALYSIS/
├── Data/
│   └── era5_2005_2025.csv
├── notebooks/
│   └── Projekt_EDA.ipynb
├── reports/
│   └── EDA_ERA5_Kowalski.pdf
└── README.md