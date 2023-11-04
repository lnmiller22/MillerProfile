# Data Visualization #2 Assignment
[Return to Home Page](/README.md)

All information in the forthcoming assignment was pulled from the OECD "General Government Debt" dataset. 
> OECD. General Government Debt. Updated 2023. Distributed by OECD Data. https://data.oecd.org/gga/general-government-debt.htm.

## Part I: General Government Debt (2019)
The data visualization below depicts the 2019 Debt-to-GDP ratio for all countries included in the OECD dataset. The United States ratio is highlighted in blue, and the international average is highlighted in red. This visualization is valuable in understanding not only the position of individual nations, but the relative scale of country-by-country Debt-to-GDP ratios to each other in a uniform time frame.

<iframe src="https://data.oecd.org/chart/7ePt" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7ePt" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</a></iframe>

## Part II: Debt-to-GDP Ratios Over Time (1995 - 2022)            
The data visualization below depicts a "heat map" for Debt-to-GDP ratios through time (1995 - 2022) for countries included in the OECD dataset. The "warmer" (redder) the color, the higher the value. Intuitively, then, the "cooler" (bluer) the color, the lower the value. While the sheer mass of data may at first be slightly overwhelming, unlike the visualization in Part I, this graphic is valuable in understanding _changes over time_ for countries in their internal Debt-to-GDP ratios. In addition, it is valuable to observe where certain countries began--where applicable-- their substantial growth of debt, while others remained quite constant to themselves. Finally, this graphic is valuable in its ability to clearly demonstrate where data points are **missing**, preventing any potential miscontruction of data through confusing trends (e.g. a ratio suddenly dropping down to 0) or improper statistics (e.g. skewing mean, median, or range) that otherwise may have occured through the implementation of alternative types of data visualization.

<div class='tableauPlaceholder' id='viz1699041982406' style='position: relative'><noscript><a href='#'><img alt='Debt-to-GDP Ratios Over TimeSource: Organization for Economic Co-operation and Development(OECD. General Government Debt. Updated 2023. Distributed by OECD Data. https:&#47;&#47;data.oecd.org&#47;gga&#47;general-government-debt.htm.) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DataViz2Book&#47;DebttoGDPRatiosOverTime&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DataViz2Book&#47;DebttoGDPRatiosOverTime' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DataViz2Book&#47;DebttoGDPRatiosOverTime&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div><script type='text/javascript'>                    
  var divElement = document.getElementById('viz1699041982406');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';  
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Part III: Original Visualizations
The present section contains two graphics I developped independently using the provided OECD dataset. Rationale for each of the visualizations are provided in turn below.

### Attempt I: US Position in Average Debt-to-GDP Ratio (2010 - 2020)
The following visualization was one of two graphics I created for this exercise. As can be seen, this first attempt wound up too similar to the initial graphic developped on the OECD website to fit appropriately within the scope of this project. However, I felt it was important to include on this site as it was ultimately extremely valuable for me as I was coming to understand _both_ the OECD dataset and the available functions of Tableau as a software. 

<div class='tableauPlaceholder' id='viz1699054666736' style='position: relative'><noscript><a href='#'><img alt='Nation Position in Average Debt-to-GDP Ratio (2010 - 2020)Source: Organization for Economic Co-operation and Development(OECD. General Government Debt. Updated 2023. Distributed by OECD Data. https:&#47;&#47;data.oecd.org&#47;gga&#47;general-government-debt.htm.) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DataViz2BookPart3&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DataViz2BookPart3&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DataViz2BookPart3&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                

<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1699054666736');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

For the last portion of this assignment, I was interested in creating a visualization that would explore the **mean Debt-to-GDP ratio** throughout specific subsets of time. As uncovered in Part II, there are several countries that are missing data either prior to a certain date or in some more recent intervals. In particular, a fair portion of country data is missing for 2022, when (at the time of publication in 2023) the OECD dataset did not yet have data for all historically included nations. 

For this reason, it was important to create a visaulization that auto-generated on a time frame in which nearly all countries had recorded Debt-to-GDP ratios to prevent a potential misrepresentation of mean values. After analysis, **2010 to 2020** proved the most encompasing time period based on the available data. In addition, this time period provides unique insight to the state of nations' ratios prior to/just at the onset of  Covid-19. In my opinion, when looking over such a relatively significant spanse of time, post-Covid data would be best represented on its own visualization meant to track pandemic-related trends. The only two countries with missing data entries in the 2010 to 2020 time period were Colombia and Iceland, and as such these two countries were removed from the visualized dataset to prevent potential misinterpretation of mean values (including, for example, a "0" for the 2014 value of Iceland when there was no recorded data would skew the country's overall average ratio).

In addition auto-generating to the 2010 - 2020 time window, I felt it important to auto-generate the graphic highlighting the United States. For the sake of this assignment and the nation of the course's instruction, I assumed that the US would be the primary audience for the grahic's usage or potential embedding in news articles. As such, it was logical to pull-out the nation in the visualization's primary green color, highlight the country name on the X-axis, and "gray out" the remaining nations in the graphic's opening form. Finally, countries were organized in ascending order based upon average Debt-to-GDP ration **during the selected time frame** to be easily comprehensible in left-to-right relative growth country-by-country. The ordering of the countries is flexible to the alteration of the user's selected time frame.

Finally, I felt it was important to maintain both flexibility and perspective on the visualization. 
> **Flexibility** Users are able to toggle the date window to adjust their ideal time frame as desired. I greatly appreciated this feature on the OECD website, and found it valuable to work out how to incorporate a similar visual on my own graphic. Of course, it is assumed that in use the visualization would be presented with a caption and/or in-text disclaimer **why** the author felt that 2010 to 2020 was the most representative time window of the dates at hand. 

> **Flexibility** If users are interested in countries other than just the US, they are able to use the "Highlight Location" feature to draw-out or find the nation they are most interested in. Upon the selection of another country, Tableau will bold and highlight the chosen country in a manner identical to how the US presents upon opening the visualization. Of course, if users are interested in seeing all nations at once, the highlighted nation may be easily unselected using the same "Highlight Location" dropdown menu, and all countries will appear in the uniform green color. 

> **Perspective** An "Average International Debt-to-GDP Ratio" trend line was added to the graph to add perspective to individual country position relative to the remainder of the nations at any given time period. The trend line will adjust to mirror the time period chosen by whomever is engaging with the visual.

As a whole, while this visualization ended up completely accidentally and wholly similar to the original OECD visualization, it is valuable in making a large dataset **easily comprehensible** on both individual country and holistic international levels, with provided flexibility for time frame and users' primary country (or countries) of interest. As a whole, the visualization fits uniquely into the larger story being told in part with the graphic in Part II. 

### Attempt II: ____
Upon realizing the first visualization's striking similarity to the original bar graph exported in this assignment, I moved forth to create the following. 
