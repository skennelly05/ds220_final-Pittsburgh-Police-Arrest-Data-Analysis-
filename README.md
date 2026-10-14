# Pittsburgh Police Arrest Data Analysis
 
Final project for DS 220. I took a dataset of Pittsburgh Police arrests and dug into when, where, and for what offenses people get arrested in the city.
 
## The data
 
The dataset is `arrests.csv` in this repo: 66,485 arrest records with 17 variables, covering 94 neighborhoods. Each row is one arrest, with details like the offense, time, neighborhood, and the age, gender, and race of the person arrested.
 
## What I did
 
I did everything in Python with Pandas and Matplotlib. The main cleaning problem was that some arrests list several offenses in one field, so I split those apart so each offense gets counted on its own. After that I looked at arrests by gender, offense type, time of day, and neighborhood, and made 7 visualizations.
 
## What I found
 
- Arrests peak late in the evening and in the early morning hours.
- The Central Business District had the most arrests (4,440), followed by South Side Flats (3,497).
- I also compared race and age breakdowns across the most common offenses.
## What I'd recommend
 
Based on those patterns, I put together a three-part plan for reducing crime hotspots:
 
1. Targeted late-night patrols and youth programs in the busiest areas
2. Bias-awareness training, along with a review of how charges are filed
3. Better lighting and CCTV at locations with a lot of offenses
## Files
 
- `arrests.csv`: the raw data
- `analysis.ipynb`: the Jupyter notebook with all the code, cleaning steps, and charts
- `index.html`: an HTML export of the notebook, easier to read without running anything
To see the analysis, open the HTML file in your browser. To run it yourself, open the notebook in Jupyter with `arrests.csv` in the same folder.
 
## About me
 
I'm Sean Kennelly, a Penn State student studying Applied Data Sciences in the College of IST. You can find me on [LinkedIn](https://www.linkedin.com/in/seanjosephkennelly).
