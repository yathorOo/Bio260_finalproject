# Bio260_finalproject: Analysis of online ads for Data Science jobs

##Background and Motivation 
As someone who is thinking about going into the field of Data Science and Machine Learning, I have looked through online job ads for data scientists and got overwhelmed by the amount of skills required. It would take a very long time to learn the whole repertoire of data science tools. 

To help decide which tools to learn first, I decided to look at which data science skills are currently most in-demand by employers in major cities in Canada and U.S.

Just like any sane person would do these days, I googled "web scraping indeed" to see if I can scrape job ads to analyse them. I came across [this awesome blog](https://jessesw.com/Data-Science-Skills/) by Jesse Steinweg-Woods published in March 2015. He looked at the data science tools mentioned in the job ads aggregated by [indeed.com](http://www.indeed.com/) for Seattle, Chicago, San Francisco, New York and Nationwide.  

His findings from nationwide search suggested that Python is much more in demand than R. This really intrigued me to see if the trends he found a year ago have changed. 

***You can find the R Markdown used for this project under `project_rmarkdown.Rmd`***

**Notes about the datasets**
* `master_39cities` 
    + Column `Term` = Name of data science tools
    + Column `DAnalyst`= % of job ads for data analysts that contained the `Term`
    + Column `DScientist` = % of job ads for data scientists that contained the `Term`
    + Column `DArchitect` = % of job ads for data scientists that contained the `Term`
    + Column `DEngineer` = % of job ads for data scientists that contained the `Term`
    + Column `City` = U.S. Cities
    + Column `State`= U.S. States
* `master_53cities`
    + Same as `master_53cities` 
* `num_posting_US` 
    + Column `City, State`
    + Column `DAst_num` = Number of job ads for Data Analysts in each of the 53 cities
    + Column `DS_num`   = Number of job ads for Data Scientists in each of the 53 cities
    + Column `DAr_num`  = Number of job ads for Data Architects in each of the 53 cities
    + Column `DE_num`   = Number of job ads for Data Engineers in each of the 53 cities
* `canada1`: Job ad data for data analysts in Canada
    + Column `Term` = Name of data science tools
    + Column `Num_Postings` = Percent of job ads that contain the `Term`
* `canada2`: Job ad data for data scientists in Canada
* `canada3`: Job ad data for data architects in Canada
* `canada4`: Job ad data for data engineers in Canada
* `national1`: Job ad data for data analysts in U.S.
* `national2`: Job ad data for data scientists in U.S.
* `national3`: Job ad data for data architecs in U.S.
* `national4`: Job ad data for data engineers in U.S.

* `53cities_alljobs` folder: Job ad data collected from scraping indeed.com for 53 American cities. 
    + The job titles searched are "Data Analyst", "Data Scientist", "Data Architect" and "Data Engineer".
* `53_cities_separate_files`: Job ad data collected from scraping indeed.com for 53 American cities. 
    + The job titles searched are "Data Analyst", "Data Scientist", "Data Architect" and "Data Engineer".
    + The files have separate data for each job title in each city. 


