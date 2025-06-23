# StateElectionData

In this project, I used RStudio to process and combine data on 2022 electoral contests in Wisconsin. The end goal of my data transformation was to get the electoral contest data in a format to be easily filtered by county and type of contest. I completed this project on a volunteer basis with the goal of producing a summary of electoral contests in WI that went uncontested in 2022, i.e, contests that had only a Democratic candidate or only a Republican candidate. 

I obtained public data for this project from the Wisconsin Election Commission website. In addition, I used Dave’s Redistricting to manually source a list of counties corresponding to each congressional district in Wisconsin in 2022. The publicly available electoral contest data was organized in Excel spreadsheets that needed extensive cleaning, transformation, and standardization in order to obtain a data frame in which electoral candidate information was listed out repetitively for each county in which the candidate ran.

This final product of my ETL was a data export to Google Sheets, where I further processed the data into an interactive dashboard of contests by county.

The relevant files from this repo are as follows: 
•	WI_Data.Rmd
•	WI_County_Representatives.xlsx
•	WI_County_StateSenators.xlsx
•	WI_Statewide_Results.xlsx

