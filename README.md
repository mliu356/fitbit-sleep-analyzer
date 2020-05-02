# fitbit-sleep-analyzer

My initial inspiration for this data analysis experiment was the fact that I was sleeping more than ever and still waking up unexpectedly tired. I hypothesized that this was a result of my unusual circustances given the COVID-19 outbreak; without normal social activities or school demands, I was exercising more often than usual and at different times of day. This experiment was intended to discern any measurable correlations between these workouts during the day and the quality of sleep I got the following night.

There are 2 main data sources:
* Downloaded csv, json files:
  * Uses intraday data to draw correlations between workout data (time of day, intensity, duration) and sleep data (quality, duration, sleep/wake time)
  * File: fitbit-intraday-analysis.ipynb
* Web API:
  * Uses aggregate day data to analyze correlations between sleep and daily activity level
  * Files:
    * fitbit-data-cleaner.ipynb
    * fitbit-data-analysis.ipyn

Setup instructions can be found in their respective Jupyter notebooks.

# Conclusions & Future Projects
I'm glad I completed this project because I gleaned some interesting insights and got to practice my data science skills, but given the small sample size, I cannot come to any generalizable conclusions. I would like to re-run these experiments in a few months when I have more data to shield against outliers. For context, at the time of this initial run, I've only been wearing this Fitbit for ~20 days.

Further analyses could include using  more detailed minute-by-minute data (accessible via account export as csv or json file) to draw more precise correlations. I would also be interested in incorporate other mediums, like browser or mobile tracking to discern if the type of content and time of day accessed plays a role in sleep quality. I have installed activity trackers on both my laptop and my computer and may potentially update this project when I've collected enough data from those.
