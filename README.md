# TOK SE KA

## Setup Environment - Anaconda
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
```

## Setup Environment - Shell/Terminal
```
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Run steamlit app
```
cd dashboard
streamlit run dashboard.py
```

## Project Description
This project analyzes bike sharing data from 2011-2012 to understand rental patterns and factors affecting bike rentals. The analysis focuses on:
- Seasonal trends in bike rentals
- Impact of holidays vs non-holidays
- Weather influence on rental behavior

## Features
- Interactive Streamlit dashboard with:
  - Date range selection
  - Monthly rental trends visualization
  - Seasonal comparison charts
  - Holiday vs Non-holiday hourly patterns
  - Weather impact analysis
- Data analysis includes:
  - Over 17,000 data points analyzed
  - Seasonal pattern identification
  - Peak usage time analysis
  - Weather correlation study

## Key Findings
1. Seasonal Impact
   - Fall season shows highest rental numbers
   - Spring has lowest average rentals
   - Clear pattern of seasonal influence on rental behavior

2. Holiday vs Working Day Analysis
   - Working days show two peak times (8 AM and 5-6 PM)
   - Holidays have more distributed rental pattern throughout 12-4 PM
   - Different usage patterns suggest commuting vs leisure purposes

3. Weather Influence
   - Clear weather: 71.0% of rentals
   - Misty conditions: 24.2% of rentals
   - Light snow: 4.8% of rentals
   - Heavy rain: Minimal impact (less than 0.1%)

## Tools & Technologies
- Python
- Pandas & NumPy for data analysis
- Matplotlib & Seaborn for visualization
- Streamlit for dashboard creation
