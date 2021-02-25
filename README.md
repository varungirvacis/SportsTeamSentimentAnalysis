# SportsTeamSentimentAnalysis
Sentimental Analysis using Rosette API of Cricket Teams
The user selects the cricket team from a drop down to find the current sentiment of public in the market. The latest information about the team from https://www.firstpost.com is gathered and is stored in Azure cloud database.
The data from Azure is then passed into Rosette API and the polarity of the sentiment is displayed in a web form.
The data is gathered using beautiful soup library(bs4 in python). The gathering, analysis and storage is handled through python. The front end form is in .Net
