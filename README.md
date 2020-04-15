# INSC590-OSF Project: Group 1  
Reproducible README:  
This README.md file was generated on 2020-04-15
## DOI:

# GENERAL INFORMATION
**1. Title of Project:** OSF INSC 590 - Group 1 - The Impact of Money Invested and the Return in  Medals at the Summer Olympics , 1960-2008

This project makes use of a variety of open-source data to explore the impact of money invested in Olympic programs around the world and the return realized in terms of medals won. Like scientific data, quantitative studies in the humanities rely on well-sourced, accurate data. Increasingly powerful computers allow for the automated harvesting of extremely large datasets. These datasets, in turn, make it possible to explore a broad range of questions. The question that interests us, in particular, is whether patterns emerge when exploring the financial investment in Olympic sports that always correlate with the number of medals earned. Or, are there cases where countries, particularly those that are smaller and less well funded, enjoy a consistent or sustained success in certain events.
  
**2. URL to OSF Project:** https://osf.io/9bq5r/
  
**3. Contributor Information**

**Name:** Tom Finn  
**Institution:** University of Tennessee, Knoxville  
**Email:** tfinn@vols.utk.edu  
**ORCID ID:** 0000-0002-7892-6669

**Name:** Hansen Karyakose  
**Institution:** University of Tennessee, Knoxville  
**Email:** hkaryako@vols.utk.edu  
**ORCID ID:** 0000-0002-7001-1739 
   
**Name:** John Metz  
**Institution:** University of Tennessee, Knoxville  
**Email:** jmetz3@vols.utk.edu 
**ORCID ID:** 0000-0002-6631-9810
  
**Name:** Chris Sanders  
**Institution:** University of Tennessee, Knoxville  
**Email:** csander9@vols.utk.edu  
**ORCID ID:** 0000-0001-9013-8780


# DATA & FILE OVERVIEW

## Directory of Files  

**Filename:** Cost_per_event_cost_per_athlete_Olympics.csv  
**Short description:** List of Olympic games by year and location, including a breakdown of cost per event and cost per athlete  
**Additional Notes on File Relationships, Context, Content, or License:** Retreived from Olympics - @Sports – cost overruns - https://data.world/sports/olympics.  
**Data Pulled From:** The Oxford Olympics Study 2016: Cost and Cost Overrun at the Games study by Bent Flyvbjerg, Allison Stewart, and Alexander Budzier at Oxford.  

**Filename:** Medal Count.csv    
**Short description:** List of Olympic games by year and location, including a breakdown of total medals awarded per game, as well as a breakdown of number of medals won by gender  
**Additional Notes on File Relationships, Context, Content, or License:** DataBlog (2016). Olympic medal winners: every one since 1896 as open data. The Guardian. Retreived from https://www.theguardian.com/sport/datablog/2012/jun/25/olympic-medal-winner-list-data#data. Data provided by the IOC Reference and Research Service.  
**Data Pulled From:** DataBlog (2016). Summer Olympic medallists 1896 to 2008. The Guardian. Retrieved from https://docs.google.com/spreadsheets/d/1zeeZQzFoHE2j_ZrqDkVJK9eF7OH1yvg75c8S-aBcxaU/edit#gid=0.   
  
**Filename:** Medals by Country.csv  
**Short description:** Total Olympic medals won by country, including breakdown by type of medal (gold/silver/bronze)  
**Additional Notes on File Relationships, Context, Content, or License:** DataBlog (2016). Olympic medal winners: every one since 1896 as open data. The Guardian. Retreived from https://www.theguardian.com/sport/datablog/2012/jun/25/olympic-medal-winner-list-data#data. Data provided by the IOC Reference and Research Service.  
**Data Pulled From:** DataBlog (2016). Summer Olympic medallists 1896 to 2008. The Guardian. Retrieved from https://docs.google.com/spreadsheets/d/1zeeZQzFoHE2j_ZrqDkVJK9eF7OH1yvg75c8S-aBcxaU/edit#gid=0.   
  
**Filename:** Medals by individuals.csv  
**Short description:** List of Olympic game medallists per year, sport, discipline, gender and event  
**Additional Notes on File Relationships, Context, Content, or License:** DataBlog (2016). Olympic medal winners: every one since 1896 as open data. The Guardian. Retreived from https://www.theguardian.com/sport/datablog/2012/jun/25/olympic-medal-winner-list-data#data. Data provided by the IOC Reference and Research Service.  
**Data Pulled From:** DataBlog (2016). Summer Olympic medallists 1896 to 2008. The Guardian. Retrieved from https://docs.google.com/spreadsheets/d/1zeeZQzFoHE2j_ZrqDkVJK9eF7OH1yvg75c8S-aBcxaU/edit#gid=0.   
  
**Filename:** outturn sports-related costs of the Olympic Games.csv  
**Short description:** List of Olympic games, including location, whether summer or winter, number of events, number of athletes, and cost of the games  
**Additional Notes on File Relationships, Context, Content, or License::** Retreived from Olympics - @Sports – cost overruns - https://data.world/sports/olympics.  
**Data Pulled From:** The Oxford Olympics Study 2016: Cost and Cost Overrun at the Games study by Bent Flyvbjerg, Allison Stewart, and Alexander Budzier at Oxford.  

**Filename:** Team Events.csv  
**Short description:** Total Olympic medals won in team events by country  
**Additional Notes on File Relationships, Context, Content, or License:** DataBlog (2016). Olympic medal winners: every one since 1896 as open data. The Guardian. Retreived from https://www.theguardian.com/sport/datablog/2012/jun/25/olympic-medal-winner-list-data#data. Data provided by the IOC Reference and Research Service.  
**Data Pulled From:** DataBlog (2016). Summer Olympic medallists 1896 to 2008. The Guardian. Retrieved from https://docs.google.com/spreadsheets/d/1zeeZQzFoHE2j_ZrqDkVJK9eF7OH1yvg75c8S-aBcxaU/edit#gid=0.   

## Data Descriptions
### Filename: Cost_per_event_cost_per_athlete_Olympics.csv  
**Number of Variables:** 6  
**Number of Cases:** 25  
**Variable List:**

>**A. Name:** Games  
**Description:** City hosting the Olympic games  
  
>**B. Name:** Year  
**Description:** Year of the Olympic games  
  
>**C. Name:** Country  
**Description:** Country hosting the Olympic games  
  
>**D. Name:** Type  
**Description:** Winter or Summer games  
  
>**E. Name:** Cost per event in millions. USD    
**Description:** Cost of the games per event in millions USD
  
>**F. Name:** Cost per athlete in millions. USD  
**Description:** Cost of the games per athlete in millions USD
  

### Filename: Medal Count.csv  
**Number of Variables:** 20 
**Number of Cases:**  117
**Variable List:**  
  
> **A. Name:**   Edition
**Description:** Year of the Olympic Games
     
> **B. Name:**   Bronze
**Description:** Total number of Bronze medals awarded in that Olympic games
   
> **C. Name:**  Gold
**Description:** Total number of Gold medals awarded in that Olympic games

> **D. Name:**   Silver
**Description:** Total number of Silver medals awarded in that Olympic games
     
> **E. Name:**   Grand Total
**Description:** Total number of medals awarded in that Olympic games
   
> **F. Name:**  City
**Description:** City in which Olympic games were held

> **G. Name:**  Country
**Description:** Country in which Olympic games were held
     
> **H. Name:**  Count of City  
**Description:** Number of times that city hosted Olympic games
   
> **I. Name:**  Count of Country
**Description:** Number of times that country hosted Olympic games

> **J. Name:**   Bronze Men
**Description:** Number of Bronze medals awarded to men in that Olympic games
     
> **K. Name:**   Bronze Women
**Description:** Number of Bronze medals awarded to women in that Olympic games
   
> **L. Name:**  Gold Men
**Description:** Number of Gold medals awarded to men in that Olympic games

> **M. Name:**   Gold Women
**Description:** Number of Gold medals awarded to women in that Olympic games
     
> **N. Name:**   Silver Men
**Description:** Number of Silver medals awarded to men in that Olympic games
   
> **O. Name:**  Silver Women
**Description:** Number of Silver medals awarded to women in that Olympic games

> **P. Name:**   Men
**Description:** Total number of medals awarded to men in the Olympic games from 1896 to 2008
     
> **Q. Name:** Women  
**Description:** Total number of medals awarded to women in the Olympic games from 1896 to 2008
   
> **R. Name:**  Count of Gender Men
**Description:** Total number of medals awarded to men in that year’s Olympic games 

> **S. Name:**   Count of Gender Women
**Description:** Total number of medals awarded to women in that year’s Olympic games 
     
> **T. Name:**   Count of Gender Grand Total
**Description:** Total number of medals awarded to men and women in that year’s Olympic games 
   
### Filename: Medals by Country.csv
**Number of Variables:** 13 
**Number of Cases:**  306
**Variable List:**  
  
>**A. Name:**   NOC
**Description:** National Olympic Committee code for the country
     
>**B. Name:**   Country
**Description:** Name of the country
   
>**C. Name:**  Total
**Description:** Number of medals won by that NOC/Country

>**D. Name:**   Bronze
**Description:** Total number of Bronze medals awarded to that NOC/Country
     
>**E. Name:**   Silver
**Description:** Total number of Silver medals awarded to that NOC/Country
   
>**F. Name:**  Gold
**Description:** Total number of Gold medals awarded to that NOC/Country

>**G. Name:**   Grand Total
**Description:** Number of medals won by that NOC/Country
     
>**H. Name:**   Year
**Description:** Year of the Olympic games
   
>**I. Name:**  UK
**Description:** Number of medals won by the UK during that year’s Olympic games

>**J. Name:**  USSR
**Description:** Number of medals won by the USSR during that year’s Olympic games
     
>**K. Name:** Russia  
**Description:** Number of medals won by Russia during that year’s Olympic games 
   
>**L. Name:**  USA
**Description:** Number of medals won by the USA during that year’s Olympic games

>**M. Name:**  China
**Description:** Number of medals won by China during that year’s Olympic games


### Filename: Medals by individuals.csv
**Number of Variables:**  10
**Number of Cases:**  29,216
**Variable List:**  

>**A. Name:**   City
**Description:** City in which the Olympic games was held
     
>**B. Name:**   Edition
**Description:** Year in which the Olympic games was held

>**C. Name:**  Sport
**Description:** Broadest category of Olympic events (aquatics, athletics, gymnastics, etc)
   
>**D. Name:**  Discipline
**Description:** Narrower category of Olympic events (artistic gymnastics vs. gymnastics)

>**E. Name:**   Athlete
**Description:** Name of the medal winning athlete
   
>**F. Name:**  NOC
**Description:** National Olympic Committee code for the country of the medal winning athlete

>**G. Name:**   Gender
**Description:** Gender of the medal winning athlete
   
>**H. Name:**  Event
**Description:** Specific event in which medal was won (discus throw, long jump, etc)

>**I. Name:**   Event Gender
**Description:** Whether the event is limited to a specific gender
     
>**J. Name:**  Medal
**Description:**  Type of medal won (gold, silver, bronze)

### Filename: outturn sports-related costs of the Olympic Games.csv
**Number of Variables:**  
**Number of Cases:**  30
**Variable List:**  

>**A. Name:**   Games
**Description:** City which hosted Olympic games
     
>**B. Name:**   Year
**Description:** Year the Olympic games were held
   
>**C. Name:**  Country
**Description:**  Country which hosted Olympic games

>**D. Name:**   Type
**Description:** Summer or Winter Olympics
     
>**E. Name:**   Events
**Description:**  Number of events held in that Olympic games
   
>**F. Name:**  Athletes
**Description:** Number of athletes who competed in that Olympic games

>**G. Name:**  Cost
**Description:** Cost of that year’s Olympic games in billions of USD


### Filename: Team Events.csv
**Number of Variables:**  6
**Number of Cases:**  791
**Variable List:**  

>**A. Name:**   Country
**Description:** Country of metal count
     
>**B. Name:**  NOC Code
**Description:** National Olympic Committee country code
   
>**C. Name:**  Total
**Description:** Total medal count (gold, silver, and bronze total) 

>**D. Name:**  Gold
**Description:** Total gold medals by respective country

>**E. Name:**  Silver
**Description:** Total silver medals by respective country 

>**F. Name:**  Bronze
**Description:** Total bronze medals by respective country
  
  
# Software Requirements

All datasets in this project are in Comma Separated Value (CSV) format. This format is interoperable with a wide range of data analysis applications. As a result, these files can be used with many operating systems, including Windows, iOS, or Linux. The Project Team used Microsoft Excel and Google Sheets to view these data.
  
# Reproducibility Notes
  
# License
  
This project is licensed under a Creative Commons Attribution 4.0 International Public License (CC by Attribution 4.0 International)

# Acknowledgments

The Project Team would like to acknowledge the following sources and individuals for the raw data used in our study:

*   Flyvbjerg, B., Stewart, A., & Budzier, A. (2016). The Oxford Olympics Study 2016: Cost and Cost Overrun at the Games (Oxford Saïd Working Paper Series RP 2016-20) (27 pp). University of Oxford. Retrieved from http://eureka.sbs.ox.ac.uk/6195/1/2016-20.pdf

* Olympic medals & host cities – Ian Greenleigh – https://data.world/ian/olympic-medals-host-cities/workspace/file?filename=Summer+Olympics+joined.csv

* Olympics - @Sports – cost overruns - https://data.world/sports/olympics

* Summer & Winter Olympic Games – Josip Korda – https://data.world/johayes13/summer-winter-olympic-games

* DataBlog (2016). Olympic Medal Winners: Every One Since 1896 as Open Data. The Guardian. Retreived from https://www.theguardian.com/sport/datablog/2012/jun/25/olympic-medal-winner-list-data#data.

