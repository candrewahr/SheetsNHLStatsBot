# SheetsNHLStatsBot
This repo contains a Google Apps Script to automate stat collection for CanesCountry

This script is used to populate a google sheet with relevant game day information about the Carolina Hurricanes - but could be reasonably modified to supply info about any NHL team.  I wrote it in an effort to make Game Preview pieces a bit less tedious over at Canes Country dot com.  Instead of having to collect all of this information by hand a few times a week, this script is set up to hit the NHL APIs -- most of which have no documentation -- and present it in a nice readable format on a Google Sheet, which is then embedded in articles.  

I do need to go into the script once a year to update the API calls for the upcoming season, and have had to make some minor modifications to the script since I wrote it in 2020. It runs once a day via a trigger I set up in the Google Apps Script environment. 

Here are the resulting Google Sheets. Opponent and stats update daily via the script. 
![image](https://user-images.githubusercontent.com/38953871/161836803-2c74d8a1-4883-4fca-970d-005eca7f9922.png)
![image](https://user-images.githubusercontent.com/38953871/161836937-50072beb-1086-4547-9790-ce1a820d261b.png)
![image](https://user-images.githubusercontent.com/38953871/161836999-3f213b6c-63bb-4957-bb95-7dd177861bfb.png)

