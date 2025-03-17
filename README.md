# CDM_Article
Code for plotting Google search trends data

Unfortunately, Python packages claiming to interface directly with Google Trends have been deprecated, requiring any trends data to be manually downloaded for analysis

To download additional data for analysis:
1. Go to trends.google.com
2. Type in a search term, for example, "Weather"
3. To look at data from YouTube specifically (as we have done here), select "YouTube Search" from the drop down that currently says "Web Search"
4. Change the time range drop down menu from "Past Day" to "2008-Present"
5. In the top right corner of the "Interest Over Time" plot, click the download button (leftmost icon); this will download a csv file which the Python script above can parse
