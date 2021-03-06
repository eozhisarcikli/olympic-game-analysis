# Analysis of the Olympic Games

## 1. Introduction

The modern Olympic Games or Olympics are leading international sporting events featuring summer and winter sports competitions in which thousands 
of athletes from around the world participate in a variety of competitions. The Olympic Games are considered the world's foremost sports 
competition with more than 200 nations participating. More than 35,000 medals have been awarded at the Olympics since 1896. The Olympic Games are 
normally held every four years, alternating between the Summer and Winter Olympics. Under this study, you will find some analysis and visualization 
about olympians and countries achievements.

## 2. Data

Data covers the years 1896 and 2012 for the summer Olympics, and the years 1924 and 2014 for the winter Olympics. This study was carried out using 
the following three data sets. 

*summer.csv*  <br/>
-Year: Year of the Olympic in "yyyy" format<br/>
-City: City ​​where the olympics took place<br/>
-Sport: The name of the sport that is the subject of the olympic<br/>
-Discipline: Detail of the related Sport<br/>
-Athlete: Olympic athlete name and surname in "SURNAME, Name" format<br/>
-Code: Three letter shortcode showing where the olympic athlete is from<br/>
-Gender: Gender of the olympic athlete (Male or Female) <br/>
-Event: Detail of the related Discipline<br/>
-Medal: Type of medal won by the olympic athlete (Gold or Silver or Bronze)<br/>

*winter.csv* <br/>
-Year: Year of the Olympic in yyyy format<br/>
-City: City ​​where the olympics took place<br/>
-Sport: The name of the sport that is the subject of the olympic<br/>
-Discipline: Detail of the related Sport<br/>
-Athlete: Olympic athlete name and surname in SURNAME, Name format<br/>
-Code: Three letter shortcode showing where the olympic athlete is from<br/>
-Gender: Gender of the olympic athlete (Male or Female) <br/>
-Event: Detail of the related Discipline<br/>
-Medal: Type of medal won by the olympic athlete (Gold or Silver or Bronze)<br/>

*dictionary.csv* <br/>
-Country: Long name of the Code showing where the olympic athlete is from<br/>
-Code: Three letter shortcode showing where the olympic athlete is from<br/>
-Population: The whole number of people or inhabitants in the related country<br/>
-GDP per Capita:  It is the economic output of the related country per person<br/>

## 3. Analysis

### 3.1 Who

-Michael Phelps, Aleksandr Dityatin and Heikki Savolainen are the athletes who won the most gold, silver and bronze medals, respectively.<br/>
-The highest decorated male athlete is Michael Phelps with 22 medals and female athlete is Larisa Latynina with 18 medals in summer olympics.<br/>
-The highest decorated male athlete is Ole Einar Bjoerndalen with 13 medals and female athlete is Stefania Belmondo with 10 medals in winter olympics.<br/>

### 3.2 When

Below graph shows the domination of the countries by year in summer olympics;

<img src="image/when_summer.png" width="900" height="400">

Below graph shows the domination of the countries by year in winter olympics;

<img src="image/when_winter.png" width="900" height="400">

### 3.3 What

Word cloud about disciplines is below for summer olympics;

<img src="image/what_summer.png" width="900" height="550">

Word cloud about disciplines is below for winter olympics;

<img src="image/what_winter.png" width="900" height="550">

### 3.4 Where

The following heatmap shows where the athletes come from and in which sports they have won medals in summer olympics.

<img src="image/heatmap_summer.png" width="900" height="650">

The following heatmap shows where the athletes come from and in which sports they have won medals in winter olympics.

<img src="image/heatmap_winter.png" width="900" height="650">