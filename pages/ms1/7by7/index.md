### MS1 / 7x7
_Made with GitHub Pages_

This page contains artifacts and notes of the 7x7 activity for Major Studio 1 (Fall 2019).

[Back to Home Page](http://dhananjaih.github.io/site/)

***

#### Prototype #1: An attempt at visualizing data through maps to inform / misinform (working title)
_October 23, 2019_

![Map of average annual e-cigarette products sold in the US (numbers as of 2016) ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/map1@4x.png)

![Map of number of e-cigarette related Lung Injury Cases reported to the CDC (10/15/2019) ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/map2@4x.png)

![Map of Lung Injury cases in the context of e-cigarette products sold ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/map3@4x.png)

![Map of e-cigarette related Lung Injury cases & Deaths reported to the CDC (10/15/2019) ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/map4@4x.png)

Following the theme of my research topic - 'how can data be visualized in a way to inform decision-making?', I attempted to explore this through a case study. Given the recent news of the impact e-cigarette use and other harmful effects, I was wondering if any data on this is available, and if so, could it be used to promote awareness and incentivize better consumer safety in the space.

**Process**

I gathered the following data:
- Average E-cigarette (& related) products sold in the US [1]. This paper aggregated monthly product sales information for 2016, from each state and product category. **The average monthly sales numbers were used to approximate the annual unit sales.** Ideally, I would have wanted to extrapolate the unit product sales for 2018/2019, but did not any reliable metrics for doing so.

- The number of Lung-Injury cases and victims reported to the CDC, that have been confirmed as attributable to e-cigarette usage [2]. The CDC provides frequently updated information on this case, and as of October 15, 2019, confirmed 1479 lung injuries and 33 victims. The organization also provides this information grouped by state.

This prototype was made using Sketch software for Mac, with an svg map of USA sourced from [3].

**Reflection**

Visualizing tabular information as a map proved to be a challenging process. The theme I wanted to promote here was that **'the severity of the issue outweighs the statistical significance'**.

- In map \#3, had I chosen to represent the lung injury cases as a percentage of the number of products sold, most of them would be invisible on this map. Instead, I chose to use defined sizes with respect to the map so that they are presented more evenly.
- The above point may also be considered as a Data Lie per Edward Tufte, since I tried to exaggerate the effects visually.
- The hidden bias here also lies in the fact that a fair number of the victims here are attributed to having used uncontrolled chemicals and substances with the Cigarettes, or were using DIY/modified products, and hence, were unregulated to begin with.
- Felt some restriction in working with a map in a software tool, and felt that it drove me to create some fairly standard charts.

###### References:
[1] Teresa W. Wang, PhD, MS1; Ellen M. Coats, MS2; Doris G. Gammon, MS2; Brett R. Loomis, MS2; Nicole M. Kuiper, MPH1; Todd Rogers, PhD2; Brian A. King, PhD, MPH. National and State-Specific Unit Sales and Prices for Electronic Cigarettes, United States, 2012–2016. [http://dx.doi.org/10.5888/pcd15.170555](http://dx.doi.org/10.5888/pcd15.170555)

[2] Centers for Disease Control and Prevention. "Outbreak of Lung Injury Associated with E- Cigarette Use, or Vaping" [https://www.cdc.gov/tobacco/basic_information/e-cigarettes/severe-lung-disease.html](https://www.cdc.gov/tobacco/basic_information/e-cigarettes/severe-lung-disease.html) (Last accessed October 15, 2019)

[3] [MapSVG - USA](https://mapsvg.com/maps/usa/)

***

#### Prototype #2: Visualizing physiologic / fitness data with context to provide insight (working title)
_October 26, 2019_

In recent years, wearable fitness devices are quite widespread, and have collected vast amounts of physiological and behavioral data. Yet this data & how it is represented is not being utilized to its potential (at least not for the consumers of these technologies).

![Sketch of Fitbit dashboard ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/fitbit-dash.jpg)
_(not real data)_

Above is a rough sketch of standard line chart generated from data off devices such as Fitbit, showing Heart Rate information recorded from a person over a 24hr period. While simple to read and observe, line charts are quite standard for displaying single channel quantitative information. However, it leaves the information to be open for interpretation, and requires closer inspection for an average consumer to gain qualitative information from this.

![Sketch of Apple Watch face ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/apple-watch-face.jpg)
_(not real data)_

Similarly, an alternate form of presenting information to its customers is illustrated in the above sketches of some Apple Watch faces. These watch faces provide slightly more qualitative information, which in certain contexts, can help one to gain a certain awareness of their activities (or lack thereof).

![Sketch of data in context of a body clock ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/clock-plot-1.jpg)
_(not real data; an approximation of heart beat information over a day with some assumed activities)_

In the sketch above, I explore similar data as the Fitbit / Apple Watch in a more relatable context of a 24-hour body clock. In my perspective, this information is better interpreted in the context of time of day, & how this may relate to the human body clock (a.k.a. circadian rhythms). The illustration shows heart rate info over a day, highlighting the average heart rate as well as the overall variation at each time stamp.

For example, the chart above shows high heart rate and variability around the 6:30 - 7am window, indicating that perhaps the individual was exercising.

Similarly, around 5 / 5:30am, the persons' heart rate dropped extremely low, indicating that perhaps the person has some sleep or heart disorder.

The clock face also provides opportunity to add additional layers of information for context.

![Sketch of data in context of a body clock 2 ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/clock-plot-daynight@2x.png)

Here, the same clock has the general day / night hours overlayed on the display, providing some additional context around the information. Other sources of data, such as activity level and temperature could also be overlayed.

In the context of sleep and activity tracking, as marketed by consumer electronic device manufacturers, having this context provides an easier interpretation. This also provides the affordance to provide some interactive tools to analyze and suggest better sleep habits for a healthier living.

###### Reflections

- This mockup aimed at trying out a particular relevant metaphor for presenting information.
- Doing this in an analog medium (pencil, pens, paper) was a lot more relaxing and allowed me to focus more on the artifact rather than the tool. As I was laying down each visual component by hand, it did force me to think about its necessity and to keep it simple so as to maximize the visual resolution and cleanliness.
- I would like to continue making additional such experimental clock faces with different combinations of data (targeted at different applications). As well as start putting together such plots with software using real datasets. I imagine viewing the shapes drawn by a person's vitals over consecutive days can yield some interesting shapes and narratives.
