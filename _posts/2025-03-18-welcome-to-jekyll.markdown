---
layout: post # should say post here, difference is that there is no title. 
title:  "Assignment 2: Driving Under the Influence: A Data-Driven Look at Trends and Hotspots"
date:   2025-03-18 10:29:55 +0100
categories: jekyll update
---

Driving under the influence (DUI) remains a significant concern for road safety, contributing to thousands of accidents each year. Our analysis of DUI incidents in San Francisco, based on data from 2003 - 2017 as this category is not found in newer data, provides a clearer picture of when and where these violations are most frequent. This information is crucial for law enforcement, policymakers, and the general public in addressing and mitigating the risks associated with impaired driving.

Data suggest that certain days of the week see higher DUI occurrences. Unsurprisingly, weekends, particularly Fridays and Saturdays, report the highest number of incidents, as seen in <i>Figure 1.1</i>. This trend aligns with nightlife and social drinking patterns, as people go out to bars, clubs, and parties. 
Further this trend is also seen on Thursdays which suggests drinking events and after-work social gatherings also contribute significantly to DUI cases. This may be a bit difficult to discern, but it is due to most arrests happening throughout the night as portrayed in <i>Figure 2</i>, making the data appear skewed by the day. Apart from the number of DUI arrests made, it can also be specified which of those were related to alcohol and drugs. As most would assume, the number of alcohol-related arrests is significantly higher than the number of drug-related arrests.

Alcohol is more widely consumed and has a more immediate effect on cognitive and motor functions, making it easier to detect in law enforcement encounters. Additionally, alcohol-related driving laws are well-established and easier to enforce compared to those related to drugs, which can vary in detection methods and thresholds for impairment. That alcohol i more widely consumed can be clearly seen in <i>Figure 1.2</i>.


<figure> 
  <iframe src="/assets/bar_plot.html" width="120%" height="500px"></iframe> 
  <figcaption style="font-style: italic; text-align: center; margin-top: 10px; color: #555;">
   Figure 1.1: The first plot is a bar plot that shows the number of arrests throughout the weekdays. Dragging the curser over the bars shows the amount of arrest in the category DUI for each weekday from 2003-2017. <br> 
   Figure 1.2: Clicking on the green button switches the plot to show the distribution of drug- and alcohol-related arrests. Dragging the curser over the bars shows the distribution of alcohol-related and drug-related arrests..
   </figcaption> 
 </figure>


As stated earlier, arrests are made primarily during the night, rising from 22:00 and falling again by 02:00 as can be seen in <i> Figure 2</i>. This is most likely due to bars closing at 2 AM[1]. The highest number of arrests occur at 00:00, but arrests remain significant at 01:00 AM and 02:00 AM. This is likely because police are aware that these are the times when people are under the influence, making them more perceptive to signs that someone might be driving impaired, as opposed to during the middle of the day.

<figure> 
  <iframe src="/assets/time_plot.html" width="120%" height="650px"></iframe> 
  <figcaption style="font-style: italic; text-align: center; margin-top: 10px; color: #555;"> 
  Figure 2: The polar plot shows what time of day arrests are made, and the radius represents the number of arrests. It can be seen that most arrests happen at 00:00. Dragging the curser over the plot one can get the amount of crimes at each time. 
  </figcaption>
 </figure>


In addition to the time trends of arrests, there is also a geographical pattern in the arrests of people driving under the influence in San Francisco. <i>Figure 3</i> illustrates how arrests happen more frequently along the major roads in different districts. This is especially visible in the main streets of the Richmond District, Sunset District, and Mission District. Furthermore, it is notable that the main street in the Mission District is heavily populated by bars and restaurants[2], confirming the hypothesis that DUIs are committed by people driving home from a night out. Apart from these areas, it is clear that the city center areas, like Tenderloin and around Union Square, have a higher number of arrests. This could be attributed to the higher concentration of patrol cars in these areas, leading to more arrests. Another reason for the higher number of arrests on larger roads leading to residential areas could be police presence in these streets or individuals being pulled over for other reasons, such as speeding, which is more likely to occur on bigger roads with more space. An example of such a road could be the main road in the Richmond District, which is a 6-lane street.

<figure> 
  <iframe src="/assets/heat_map.html" width="120%" height="500px"></iframe> 
  <figcaption style="font-style: italic; text-align: center; margin-top: 10px; color: #555;"> 
  Figure 3: This heat map shows the locations of arrests from 2003 to 2017. 
  </figcaption> 
</figure>


In conclusion, the patterns observed in DUI incidents from 2003 to 2018 in San Francisco reveal crucial insights into the factors contributing to impaired driving. The higher frequency of arrests during weekends and late-night hours aligns with social and nightlife activities, while the rise in DUI incidents on Thursday evening suggests that midweek gatherings also play a significant role. Additionally, the geographical distribution of arrests indicates that heavily trafficked streets in San Francisco, particularly near bars and restaurants, are hotspots for impaired driving. While the data provides valuable insights, further investigation into the distribution of law enforcement presence could help refine strategies for preventing DUI incidents. Furthermore, data from 2018 to present would give a more current idea of the DUI arrests in San Francisco. Ultimately, a better understanding of these trends can aid in the development of targeted interventions to reduce impaired driving and improve overall road safety.

<b>References</b>: <br> 
[1]: <https://www.latimes.com/politics/story/2022-08-24/california-lawmakers-reject-a-bill-to-extend-bar-hours-in-three-cities> <br> 
[2]: <https://www.sftravel.com/article/best-streets-bar-hopping-san-francisco>