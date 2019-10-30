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

**Reflections**

- This mockup aimed at trying out a particular relevant metaphor for presenting information.
- Doing this in an analog medium (pencil, pens, paper) was a lot more relaxing and allowed me to focus more on the artifact rather than the tool. As I was laying down each visual component by hand, it did force me to think about its necessity and to keep it simple so as to maximize the visual resolution and cleanliness.
- I would like to continue making additional such experimental clock faces with different combinations of data (targeted at different applications). As well as start putting together such plots with software using real datasets. I imagine viewing the shapes drawn by a person's vitals over consecutive days can yield some interesting shapes and narratives.

***

#### Prototype #3: Visual aesthetics & medium? (working title)
_October 27, 2019_

In the spirit of trying something fun and unusual, I wanted to try a prototype that is a little more abstract from the theme. Looking at some of my prototypes as well as precedent work in the domain, I started to think more about the visual components of data being rigid, precise, defined shapes (think circle, square, dots, lines, stars etc). While it does seem natural to use precise, defined shapes to represent precise, quantitative information, there is definitely some imprecise, qualitative information in a dataset as it relates to a domain.

There are 2 narratives shown in the prototypes here. The first one is the use of a natural, analog (and by nature, imprecise) medium to illustrate data, allowing the form to control the information. The second narrative is that this is an experimental approach to presenting the quantitative _**and**_ qualitative information in a single channel.

![Watercolor painting of a pocket calendar ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/ink-blot-v1.png)

Shown above is a watercolor illustration of a pocket calendar, with each blob of water+paint representing a specific aspect of a day. This could be a person's vitals (an extension of #P2), or mood / emotions for a day.

Taking the example of prototype \#2, the "shape" of a person's daily body clock could be embodied in the central core of the chart, while the outer uncontrolled shape could be interpreted as a longer term subjective impact on the person's health. In the context of health and wellness, if a person does not get sufficient sleep on a single day, its effects on their mood and energy can tide over to the following days of the week. This phenomenon can be observed in some of the color blobs flowing into neighboring cores.

![Watercolor painting of a wall calendar ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/ink-blotv2-1.jpg)

![Watercolor painting of a wall calendar ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/ink-blotv2-final2.jpg)

Above is another example of a wall calendar being used to map this data. If we are able to establish some experimental, quantitative way for correlating qualitative effects of health practices, this information can be translated to controlling a plotting tool which controls the amount of water and ink added to the paper, as well as other factors to control how the ink is introduced to the medium.

**Reflection**

- Fun: Playing with water and graphite / ink was a relaxing experiment.
- While a little abstract from industry applications of data viz, there is definitely some room to explore a controlled process for generating such visuals from real data.

***

#### Prototype #4: Twisting data dimensions? (working title)
_October 28, 2019_

Today, I explore ways for visualizing and analyzing ECGs (Electrocardiograms: Electrical activity of the heart).

Below: after gathering some signals, I attempted to layer consecutive beats over each other. In industry terms, this is known as a 'waterfall analysis'. It is often used by analysts and researchers to observe changes in beat morphology in various scenarios.


![Waterfall of 5 beats w color ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/5 beats overlap 1.png)
_5 overlapping beats_

![Waterfall of 15 beats w color ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/20 beats overlap 1.png)
_15 overlapping beats_

![Waterfall of 50 beats w color ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/50 beats overlap 1.png)
_50 overlapping beats_

After a while, the shapes of the individual waves gets lost and begins to coalesce into one aggregate shape, with some deviance. From an analysis point of view, it becomes hard to analze more than 5-10 beats at a time.

While browsing the internet for some references on a project, I came across Peter Saville's album cover art for the band Joy Division.

![“Unknown Pleasures”, Joy Division, promotional sticker, United Kingdom, 1979 Design: Peter Saville (United Kingdom)](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/peter-saville-2.jpg)

_Reference: Peter Saville's 1979 Album Cover Art for Joy Division's "Unknown Pleasures" ([Source](https://www.creativeboom.com/resources/jens-muellers-new-book-is-the-most-comprehensive-exploration-of-graphic-design-to-date/))_

Taking the similar concept of a topographical chart, I tried to stack the waves...

![Topography of 15 beats ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/15 beats stack 1.png)
_topography of 15 beats_

![Topography of 50 beats ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/50 beats stack 1.png)
_topography of 50 beats_

![Topography of 100 beats ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/100 beats stack 3.png)
_topography of 100 beats_

![Topography of 200 beats ](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/200 beats stack 2.png)
_topography of 200 beats_

Going through this series, to me feels as if I am "zooming out" and observe the landscape created by the chunks of signals. From this bird's eye view, it becomes easier to observe patterns as well as deviations more easily.

My interpretation of this observation is that some of Gestalt's principles of proximity and texture come into play.

Prototype \#2 talks about illustrating 'circadian' rhythms (24hr cycles) of the body. The approach here may be useful for looking at 'ultradian' rhythms (>24hr cycles e.g. 1 week, month, year) of an individual and yield interesting observations.

#### Prototype #5: Data viz in guided feedback (working title)
_October 29, 2019_

![data guided meditation](https://raw.githubusercontent.com/DhananjaiH/site/gh-pages/images/Relaxation animation_0-134.gif)
