<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# music-during-covid
A project to investigate if listening habits changed according to lockdown measures.


## Content
- [Project Description](#project-description)
- [Project Goals](#project-goals)
- [Data Workflow](#data-workflow)
- [Possible analysis](#possible-analysis)
- [Problems encountered](#problems-encountered)
- [Resources](#resources)

## Project Description  
A project to investigate if listening habits changed according to lockdown measures.

Question:
"can we see a change on streams per week during the lockdown period?"

## Project Goals
During this project we will:
* Learn how to obtain data from different sources, including APIs, open source datasets and/or scrape data from the web.
* Practice how clean data using vectorized methods.
* Begin to practice basic plotting.

## Data Workflow

* Research for possible data sources
* Create a Trello board to plan tasks
* Create a new repo on GitHub
* Think on the file structure
* Create diferent Branches on github
* Retrieve the Data from an API for the lockdown index
* Retrieve the Data from spotify 
* Merge and clean the Data from the two sources
* Try to plot some results
* Make a presentation

## Possible analysis


## Problems encountered
Throughout the project we ran into a few problems, which were an opportunity to learn more on those topics. 

#### Git
Because we wanted to avoid problems with file conflicts, we decided to use personal branches. However, because we were still unacustomend to this system it actually created some problems. We learnt how to work with branches, switching between them, resolving conflicts and how to merge. \

#### Pickles
To have a modular approach we wanted to split tasks and output a pickle after each task. However, somehow 2 of our laptops were unable to open pickle files. Because of this we reverted to working with csv files, meaning we had to redefine dtypes, columns and indexes. 

#### Empty data
After running our script to download all the csv's from Spotify, we had some errors where we could not import into pandas. It turned out 3 countries did not have any data on Spotify. We excluded this from our datasets.

## Resources


<a href='https://covidtracker.bsg.ox.ac.uk/'>Oxford COVID-19 Government Response Tracker</a>

Credits:
Hale, Thomas, Sam Webster, Anna Petherick, Toby Phillips, and Beatriz Kira (2020). Oxford COVID-19 Government Response Tracker, Blavatnik School of Government. Data use policy: Creative Commons Attribution CC BY standard.

<a href='https://spotifycharts.com/'>Spotify charts</a>


