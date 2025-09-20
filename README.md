# Oklahoma City Thunder NBA Schedule Analysis

## Project Overview
This project explores how the NBA schedule impacts Oklahoma City Thunder’s performance 
throughout the season. Beyond descriptive analysis, the project also applies **feature engineering 
and predictive modeling** to identify the key factors (travel, rest days, back-to-backs, 
time zone changes) influencing team performance and win rates.

The analysis also includes a comparison with the **Denver Nuggets** for the 2024–25 season.

## Repository Structure

okc-thunder-schedule-analysis/

data/ # Raw datasets
- schedule.csv
- schedule_24_partial.csv
- locations.csv
- team_game_data.csv

notebooks/ # Jupyter Notebooks
- schedule_project_response_mohib.ipynb

reports/ # Reports/Exports
- schedule_project_response_mohib.html

requirements.txt # Dependencies
README.md # Project documentation

## Tools & Technologies
- Python: `pandas`, `numpy`, `matplotlib`, `seaborn`
- Jupyter Notebook
- CSV datasets (NBA schedule 2014–2024, partial 2024–25 schedule, team stats, arena locations)

## Key Insights
- Identified how **back-to-back games and travel distances** affect Thunder’s win probabilities.  
- Mapped **time zone changes and travel intensity**, showing potential schedule disadvantages.  
- Compared OKC’s 2024–25 schedule preview with Denver’s, revealing differences in rest and travel.  

## How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/mohibasid/okc-thunder-schedule-analysis.git
   cd okc-thunder-schedule-analysis

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Launch Jupyter Notebook and open the analysis:
   jupyter notebook notebooks/schedule_project_response_mohib.ipynb
