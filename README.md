## An analysis of hazardous materials spill incidents in New York state in the last five years


##### Data source: 
[New York State Open Data](https://data.ny.gov/Energy-Environment/Spill-Incidents/u44d-k5fk)

##### Goal of the project: 
The dataset contains details of when and where spills occured, time taken to close the incident on file and amount of spillage recovered, if any. The idea is to look through the dataset of over 61,000 entries to find patterns in where most spills occur, what resources are affected and how much spillage is recovered. This is a work in progress and the idea is to find answers that arise from here, mostly surrounding the state government's processing of these hazardous spills.

##### Tech stack used:
- Data cleaning with [Python Pandas]("https://pandas.pydata.org/")
- Visualization using [Plotnine]("https://plotnine.readthedocs.io/en/stable/")
- [Google Maps]("https://maps.google.com/")

##### Process:
Downloaded data for five years from NY state's open data website. Cleaned and analyzed it using Pandas. I started the analyses with some basic questions to ask of the data:
1. Where did the most incidents occur?
2. What's the most common type of material spilled?
3. What's the biggest quantity of spill?
4. What are the biggest spills by each county?
5. Shortest clean up time
6. Longest clean up time
7. Most common and least common source of spills

These led to more questions which were further explored and plotted using Plotnine.

##### Repository contents
- [Jupyter Notebook with the analysis](https://github.com/areenaarora/ny-spills/blob/main/spill-data-five-years.ipynb)
- [Raw data in CSV format](https://github.com/areenaarora/ny-spills/blob/main/five-years-spill_incidents.csv)