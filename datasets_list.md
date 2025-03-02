# A. Large, Messy Datasets for Data Cleaning

## 1. NYC Taxi Trip Data (Large, messy, multiple files, datetime issues)
- **Source:** [NYC Taxi & Limousine Commission](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- **Issues:** Multiple large files, different formats (CSV, Parquet), datetime inconsistencies, missing values.

## 2. Open Food Facts (Text cleaning, multiple sources, different formats)
- **Source:** [https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)
- **Issues:** Mismatched product names, duplicate entries, missing values, varying data formats.

## 3. US Government Census Data (Multiple files, merging required)
- **Source:** [https://data.census.gov/](https://data.census.gov/)
- **Issues:** Different file structures, inconsistent formatting, missing data.

## 4. Global Power Plants (Messy dataset, multiple formats)
- **Source:** [World Resources Institute](https://datasets.wri.org/dataset/globalpowerplantdatabase)
- **Issues:** Date-time inconsistencies, missing values, text standardization.

## 5. Chicago Crime Data (Multiple files, text cleaning, date issues)
- **Source:** [https://data.cityofchicago.org/](https://data.cityofchicago.org/)
- **Issues:** Multiple CSVs, datetime formatting inconsistencies, missing values, duplicates.

#B. High-Quality Messy Datasets with Date-Time Issues

## 1. NYC Taxi Trip Data  
- **Source:** [NYC Taxi & Limousine Commission](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)  
- **Why it's good:**  
  - Large dataset (millions of rows).  
  - Datetime issues like incorrect formats, missing timestamps, and timezone problems.  
  - Multiple files (monthly data) requiring merging.  

## 2. Chicago Crime Data  
- **Source:** [Chicago Data Portal](https://data.cityofchicago.org/Public-Safety/Crimes-_-2001-to-Present/ijzp-q8t2)  
- **Why it's good:**  
  - Inconsistent datetime formats, missing values, and timezone issues.  
  - Requires text cleaning (crime descriptions).  
  - Large dataset (over 8 million rows).  

## 3. FAA Wildlife Strike Data (Airplane Bird Strikes)  
- **Source:** [FAA Wildlife Strike Database](https://wildlife.faa.gov/home)  
- **Why it's good:**  
  - Datetime inconsistencies (different formats, missing time zones).  
  - Requires merging multiple datasets (different years).  
  - Needs cleaning of airport codes and species names.  

## 4. Flight Delays and Cancellations  
- **Source:** [Kaggle - Flight Delay Data](https://www.kaggle.com/datasets/usdot/flight-delays)  
- **Why it's good:**  
  - Multiple datetime formats, missing departure times, timezone mismatches.  
  - Requires merging multiple files (airport, weather, airline data).  
  - Large dataset (millions of records).  

## 5. Traffic Accidents in the UK  
- **Source:** [UK Road Safety Data](https://data.gov.uk/dataset/road-accidents-safety-data)  
- **Why it's good:**  
  - Datetime issues (incomplete timestamps, inconsistent formats).  
  - Requires merging accident and vehicle datasets.  
  - Large dataset (over 1.5 million records).  
