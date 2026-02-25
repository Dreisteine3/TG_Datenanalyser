# 3-Step Tariff Generation

This project generates 3-Step tariff (high, standard and low tariff) based on dynamic tariff using K-Means.  
Before generating, prepare a .xlsx file with dynamic tariff prices as input file. Example: 2024_prices_Industrie_ohne_Netzentgelt.xlsx

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Dreisteine3/TG_Datenanalyser.git
cd TG_Datenanalyser
```

Create a virtual environment (recommended):

```bash
python -m venv venv
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the scripts one by one.

1. dates_grouping_with_holidays.ipynb: add a new column to input file named "group", which hints to what group the timestamps belong. (Winter/summer, weekday/weekend).  
2. Datenanalyse_mit_Trennung_Wochenende.ipynb: uses K-Means to form the 3 levels for each group of data.  
2.1 Datenanalyse_ohne_Trennung_Wochenende.ipynb: same, but no week/weekend separation.  
3. Auslösung_mit_Mind.Dauer.ipynb: for each timestamp, chooses which step is selected to form the 3-step tariff, then makes visualisations.

## Warning

Please note the absolute paths in the code must be adjusted.

## Author

Fu  
Hochschule Biberach

---

## License

MIT License
