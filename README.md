The goal of this assignment is to construct, analyze, and publish a dataset of monthly article traffic for a select set of pages from English Wikipedia from July 1, 2015 through September 30, 2023. 

For example, English Wikipedia’s text can be used under the terms of the [Creative Commons Attribution Share-Alike license] https://en.wikipedia.org/wiki/Wikipedia:Text_of_Creative_Commons_Attribution-ShareAlike_3.0_Unported_License

[Terms of use] https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

[API usage documentation] https://wikimedia.org/api/rest_v1/#/Pageviews%20data

The graphs folder contains all required graphs - 
* 1_page_requests_graph.png
* 2_top_articles_page_views_graph.png 
* 3_fewest_months_data_graph.png

The json_files folder contains the 3 json files - 
* academy_monthly_mobile_201507-202309.json
* academy_monthly_desktop_201507-202309.json
* academy_monthly_cumulative_201507-202309.json

An example row in the json file - 
{"project": "en.wikipedia", "article": "Everything_Everywhere_All_at_Once", "granularity": "monthly", "timestamp": "2020010100", "agent": "user", "views": 3515}

Here, project is the name of the project, article refers to name of the article, granulairty refers to the time duration for which web traffic is montiored, timestamp is a YYYYMMDD00 format, agent refers to who accessed it and views is the number of monthly visits.

The csv files available in csv_files were generated to make graphing easier. It has the exact same columns as the json files - 
* academy_monthly_mobile_201507-202309.csv
* academy_monthly_desktop_201507-202309.csv
* academy_monthly_cumulative_201507-202309.csv