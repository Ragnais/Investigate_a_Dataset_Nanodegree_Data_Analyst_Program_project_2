# Investigate_a_Dataset_Nanodegree_Data_Analyst_Program_project_2
In this project, I will analyze a dataset  "No-show appointments" (original source on Kaggle) and then communicate your findings about it. 
I will use the Python libraries NumPy, pandas, and Matplotlib.

The data which was used for the analyses is "noshowappointments-kagglev2-may-2016.csv" from the official website https://www.kaggle.com. The dataset includes the information about 100000 medical appointments in Brazil. In this Project we are going to analyse which is the best possible predictor of whether or not patients show up for their appointment. Does the No-show appointment depend on Age, Gender or the number of days a patient should wait between scheduling day and appointment day itself?

Results:
1 - According to the investigation, 79,8 % of the patients did not show up on the appointment.

2 - How does the Age effect the No-show-up/Show-up?

The Age of the patients was used to predict the large difference between the No-show-up and show-up groups. The mean age of the show-up was 37,8 compared to No-show-up which was 34,3. No significant differences to note.

3 - How does the Gender effect the No-show-up/Show-up?

The proportions of females and males who showed up on the appointment were calculated in order to see whether the Gender effects the Show-up rate. There were 80.5% males and 79.9% females who showed up on the appointment. No significant differences to note.

4 - How does the Days_until_appointment effect the No-show-up/Show-up?

The timeframe between scheduled date and apppointment date was investigated to see if the longer waiting period would effect the decision to not show up. The Show-up rate was better if the timeframe between scheduled and apppointment date was no longer than one month of waiting. There is a high peak of Show-Up patients if the scheduled date and appointment date were on the same week approximately.

Limitations:
There were some invalid/negative data for Age and period of days between scheduled and appointment days.
The dataset does not include the data regarding the social insurance situation and income level of the family households which could expand analyses and separate the No-shows-ups into different Social Insurance Groups and/or Income classes.

Resources:
API Reference: https://pandas.pydata.org/pandas-docs/version/0.23.3/api.html
Markdown: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#emphasis
Basic date and time types: https://docs.python.org/3/library/datetime.html
Renaming column: https://stackoverflow.com/questions/11346283/renaming-columns-in-pandas
Matplotlib Pie chart: https://pythonspot.com/matplotlib-pie-chart/
Pandas Cheat Sheet: Guide: https://www.dataquest.io/blog/pandas-cheat-sheet/
