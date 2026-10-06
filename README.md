# Syntecxhub Website Traffic Analysis

This project explores website traffic and engagement data with Python in a Jupyter notebook. It is intended to help turn analytics exports into clear business insights.

## Analysis goals

- Analyze website traffic, including sessions, users, and bounce rate.
- Identify the strongest traffic sources, such as organic, paid, and referral.
- Evaluate engagement metrics such as session duration and pages per session.
- Track conversion rates and goal completions.
- Compare high-performing and low-performing pages.
- Present the results in a business-insights dashboard.

## What the current notebook covers

The existing notebook loads an hourly traffic export and visualizes sessions and users over time, users and engagement by channel, engagement-rate distributions, engaged versus non-engaged sessions, and traffic by hour and channel.

The supplied export contains channel, date/hour, users, sessions, engaged sessions, average engagement time, events per session, engagement rate, and event count. It does not currently include page-level, conversion, or goal-completion fields, so those analysis goals require a more detailed export. The current visuals are notebook charts rather than a standalone interactive dashboard.

## Project files

- `Website Traffic Analysis.ipynb` — data preparation and exploratory visualizations.
- `data_export_1.csv` — traffic export read by the notebook.

## Run the notebook

1. Install Python and Jupyter Notebook or JupyterLab.
2. Install the libraries used by the notebook:

   ```bash
   pip install numpy pandas matplotlib seaborn
   ```

3. Keep `data_export_1.csv` in the same directory as the notebook.
4. Open and run `Website Traffic Analysis.ipynb`.

## Data and privacy

The CSV is an analytics export. Review its contents and confirm you are permitted to share it before publishing or redistributing it.
