# Impact of terrorism on european citizen

# Abstract -> Charles
A 150 word description of the project idea, goals, dataset used. What story you would like to tell and why? What's the motivation behind your project?

# Research questions
- Rise of ultra-left or ultra-right political party
- Impact on life habits of european citizen (leisure, going out habits, impact on consumption ...)
- Sentiment of religious belief and religious habits

# Dataset
In order to conduct our investigation, we will use datas from many sources. Here we draw-up a non exhaustive list of dataset we will use :
- [Comparative Political Data Set](http://www.cpds-data.org/index.php/data) contains annual political and institutional data for 36 european countries (1960-2017). All the documentation about this dataset is given in a [Codebook](http://www.cpds-data.org/images/Update2019/Codebook-Government-Composition-1960-2017.pdf). 
- [Europe Political Affiliation](https://europeelects.eu/data/) provides information on the european political affiliation from  to per country according to different survey. Data will be collected using web scrapping.
- [Global Terrorism Database](https://www.kaggle.com/START-UMD/gtd) provides informations about more than 180,000 terrorist attacks worldwide from 1970 to 2017. Datas are stored on a csv file.
- [Europe Religous Affiliation](https://www.smre-data.ch/en/data_exploring/region_cockpit#/mode/dataset_comparison/region/FRA/period/2010/presentation/table) shows the detailed religious affiliation per country from 2006 to 2015. We will collect all these datas using web scrapping. We are interested in the evolution of religious affiliation during terrorism's periods (does it increase or decrease, does it remain the same, ...).
- [European Economical Growth](https://tradingeconomics.com/api/?source=summary) provides an API available on [Github](https://github.com/tradingeconomics/tradingeconomics). We can get information about economical growth in Europe from 1996 to 2019.



List the dataset(s) you want to use, and some ideas on how do you expect to get, manage, process and enrich it/them. Show us you've read the docs and some examples, and you've a clear idea on what to expect. Discuss data size and format if relevant.

# A list of internal milestones up until project milestone 2 
## 1. Handle the raw data & general data analysis (to be done before nov. 12th)
 - [x] Check how we get data on our computer and how we can handle the large volume of data.
 - [x] Learn how the dataset is encoded, how specific the geomarkers are, and if sentiment stamps are useful to our question.
 - [x] Look at the overall distribution of the tweets' languages, and check for issues with non-standardization of Swiss German. -> also look at regional distribution.
 - [x] Look at how frequent the use of emojis is, what methods to use to handle them.
 - [x] Look into handling time dimension of data, look at distribution of tweets over time.
 - [x] See to what extent Swiss News outlets talk about mental health.
 - [x] Find potential issues with data, are there any NaN values, how can we deal with bots and spam etc. (*Read papers that might give us interesting insights)
## 2. See how we can transform the data (to be done before nov. 18th)
 - [] Look more closely into what NLP techniques work best on our data and begin to form our dictionary.
 - [] Filter the tweets down to a dataset that interests us, check if size of dataset is reasonable.
 - [] Check how we can look at the tweets in a temporal manner, what statistical tools we should use to be able to draw conclusions.
 - [] Look into ways we can visualize our data.
## 3. Work on notebook and future plans (until deadline nov. 28th)
 - [x] Work on properly commented notebook that can be read by people outside the team.
 - [x] Have a nice visualisations and first results in notebook.

# Questions for TA -> tout le monde
Add here some questions you have for us, in general or project-specific.
