## Dataquest Python Project 350 in Power BI
The data loading and cleaning steps of the Dataquest Python Project 350 - Profitable App Profiles for the App Store and Google Play Markets were done in Power BI. The repo with the Python Project can be found [here](https://github.com/pilardib/python-project-350-dataquest).

#### Data cleaning process:
- Drop duplicates
- Drop faulty entries
- Remove entries that have non-English characters using _M_ formula in Power Query
- Values in number of downloads is a string. The text characters were removed and the type changed to numbers
- Consider only free apps

#### Analysis:
- Frequency table that shows categories ranked by number of apps
- Group apps by most popular in each category (table created using _DAX_ that shows the top 3 apps in each category)
  - a category may have more apps, however the average number of installs (or ratings in the case of the AppleStore) was used to determine which categories are more popular as well as their more popular apps
 
A PDF with a screenshot is included and please note the Apple Store and Google Play Store data are displayed in slightly different ways (I wanted to try different ways to display a list of the most popular apps in each category).
