# Data Visualization #2 Assignment
[Return to Home Page](/README.md)

## Part I: General Government Debt (2019)
<iframe src="https://data.oecd.org/chart/7ePt" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7ePt" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</a></iframe>

## Part II: Debt-to-GDP Ratios Over Time (1975 - 2022)            
<div class='tableauPlaceholder' id='viz1699041982406' style='position: relative'><noscript><a href='#'><img alt='Debt-to-GDP Ratios Over TimeSource: Organization for Economic Co-operation and Development(OECD. General Government Debt. Updated 2023. Distributed by OECD Data. https:&#47;&#47;data.oecd.org&#47;gga&#47;general-government-debt.htm.) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DataViz2Book&#47;DebttoGDPRatiosOverTime&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DataViz2Book&#47;DebttoGDPRatiosOverTime' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DataViz2Book&#47;DebttoGDPRatiosOverTime&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div><script type='text/javascript'>                    
  var divElement = document.getElementById('viz1699041982406');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';  
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Part III: US Position in Average Debt-to-GDP Ratio (2010 - 2020)
<div class='tableauPlaceholder' id='viz1699054666736' style='position: relative'><noscript><a href='#'><img alt='Nation Position in Average Debt-to-GDP Ratio (2010 - 2020)Source: Organization for Economic Co-operation and Development(OECD. General Government Debt. Updated 2023. Distributed by OECD Data. https:&#47;&#47;data.oecd.org&#47;gga&#47;general-government-debt.htm.) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DataViz2BookPart3&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DataViz2BookPart3&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DataViz2BookPart3&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                

<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1699054666736');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

For the last portion of this assignment, I was interested in creating a visualization that would be set to explore the **mean Debt-to-GDP ratio** throughout specific subsets of time. As uncovered in Part II, there are several countries that are missing data either prior to a certain date, or in some more recent intervals. In particular, a good portion of country data is missing for 2022, when (at the time of publication in 2023) the OECD dataset did not yet have data for all countries. 

For this reason, it was important to create a visaulization that auto-appeared on a time frame in which nearly all countries had recorded Debt-to-GDP ratios to prevent a potential misrepresentation of mean values. After analysis, 2010 to 2020 proved the most encompasing time period based on available data. In addition, this time period provides unique insight to the state of nations' ratios prior to/just at the onset of  Covid-19. In my opinion, when looking over such a relatively significant spanse of time, post-Covid data would be best represented on its own visualization meant to track pandemic-related trends. The only two countries with missing significant data entries in the 2010 to 2020 time period were Colombia and Iceland, and as such these two countries were removed from the visualized dataset to prevent potential misinterpretation of mean values (including, for example, a "0" for the 2014 value of Iceland when there was no recorded data would skew the country's overall average ratio). 
