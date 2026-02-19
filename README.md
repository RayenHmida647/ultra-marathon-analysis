\#  Ultra Marathon Performance Analysis - USA 2020



\##  Project Objective

This project analyzes the performance of runners in \*\*50km and 50-mile races\*\* in the \*\*United States during 2020\*\*. The goal is to compare performance by gender and study the impact of seasons on average speed.



\##  Dataset

\- \*\*Source\*\*: `TWO\_CENTURIES\_OF\_UM\_RACES.csv` (Data uploaded from Kaagle)

\- \*\*Volume\*\*: over \*\*7 million rows\*\* in the original file

\- \*\*Filtering\*\*: USA races, year 2020, distances 50km and 50mi → \*\*26,090 rows analyzed\*\*



\##  Tools \& Libraries

\- \*\*Python\*\*: main programming language

\- \*\*Pandas\*\*: data cleaning, filtering, and transformation

\- \*\*Seaborn / Matplotlib\*\*: data visualization (histograms, violin plots)

\- \*\*Jupyter Notebook\*\*: development environment





\##  Key Results



\### Average Speed by Distance and Gender



| Distance | Gender | Average Speed (km/h) |

|----------|--------|----------------------|

| 50km | Female | 7.08 |

| 50km | Male | 7.74 |

| 50mi | Female | 6.83 |

| 50mi | Male | 7.25 |



\### Main Findings

\- \*\*Gender gap\*\*: approximately \*\*0.66 km/h\*\* on 50km, \*\*0.42 km/h\*\* on 50 miles

\- \*\*Fastest season\*\*: Spring (average 7.67 km/h)

\- \*\*Slowest season\*\*: Summer (average 6.87 km/h)



\##  Visualizations Preview

!\[Count of race length by athlets gender](count\_of\_race\_length.png)

!\[Number of athlets and their average speed](histogram\_50mi\_speed.png)

!\[Average speed length by athlets gender](average\_speed\_and\_gender.png)



\##  How to Run the Project



1\. \*\*Clone this repository\*\*

&nbsp;  ```bash

&nbsp;  git clone https://github.com/RayenHmida647/ultra-marathon-analysis.git

&nbsp;  cd ultra-marathon-analysis

2\. \*\*Open the project on Jupyter Notebook or VSCode

