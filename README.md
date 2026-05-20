# Charting the Grind

A project for the **Information Visualization 2025/26 course** about
understanding **personal study habits** through the visual exploration of a
manually self-tracked study log, collected over roughly a month of study
sessions.

The website is live at [epistrephein.github.io/charting-the-grind](https://epistrephein.github.io/charting-the-grind/)

## Repository structure

- `notebook.ipynb`: the Jupyter Notebook where I performed all the data
  processing and created the visualizations.
- `data/study_sessions.xlsx`: the original Excel file where I recorded all my
   study sessions, with columns for date, start time, finish time, topic,
   activity, location, time of day and productivity score. The sheet was
   manually filled in by me every day on [Google Sheets](https://docs.google.com/spreadsheets/d/16gifeVjLju1ka6WynBZMFstMqIVC_5-OB-Xa94HJsSI/edit?usp=sharing).
- `data/study_sessions.csv`: the exported CSV version of the original Excel
  file, which I used as data source for the Python code.
- `charts/`: a folder where I saved the static jpg images of the charts created
  in the notebook.
- `website/chart.html`: the interactive version of the chosen main chart,
  created with Plotly and exported as a standalone HTML file to embed as an
  iframe in the website.
- `website/index.html`: the main page of the website, with the narrative
  accompanying the main chart and the embedded interactive version.

## Credits
- [Tommaso Barbato](https://github.com/epistrephein)
