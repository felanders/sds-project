# sds-project

This GitHub-Repository is a collection of files, scripts and data used for the course Social Data Science at ETH Zürich. 
Within this course, the following research questions were tackled: 

  - Is political party affiliation reflected in Twitter behaviour? 
  - Can party divisions therefore already become visible in advance?
  
For this analysis, the political systems of the USA and Italy have been analysed. This repository is divided into folders that contain files related to each country. For the US, all written code is contained in the file 'US_network_analysis.Rmd'. For Italy, the scripts are clustered as follows:
- 'Create-list-of-users.Rmd', contains the code used to generate a list of twitter profiles of deputies in the italian chamber.
- 'Web-scraping.ipynb' is a Jupyter notebook that was used to scrape the ground truth of deputies and  their party affiliation.
- 'Create-networks.Rmd', contains the code used to create the neworks for the whole chamber and the party split of PD and IV (the respective networks where saved in th "retweet.\*.rds" files)
- 'Analysis.Rmd', contains the code used for analysing the networks.
