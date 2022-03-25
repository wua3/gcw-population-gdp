# Global inequalities: visualizing comparisons of GDP, population from 1960 to 2018 
Data visualizations created from the figures of Appendix 1 (The World in 1960: The 25 Most Populous Countries) and Appendix 2 (The World Today: The 25 Most Populous Countries (plus South Korea) in 2018) of Vincent Bevins's 2020 book [The Jakarta Method](https://vbpublic.wpcomstaging.com/book/). `/data/scans.pdf` has the original figures, where you can see Bevin's notes on sourcing & any irregularities. My data is entirely drawn from Bevins's; this is a visualization exercise.

My visualizations show shifts and preservations of economic output by country over the last half century. Particularly, the context I'd like to highlight is of the promises and arguments of the Cold War as both a global phenomenon, and also as a huge part of why our world is organized and exists the way it does today. We can consider the 20th century movement of Third-World-ism, where countries sought to establish and protect their visions of self-determination, free develop their own independent futures independent of major power blocs. Such coming togethers like the Bandung Conference of 1955 sought to forge this vision in community among countries that identified themselves as part of the Third World, an alternative to the two dominant competing visions of Cold War modernity -- that of the United States and that of the Soviet Union. Yet half a century later, what kind of successes has been allowed, and within whose rules? These visualizations reflect one aspect of the decline of Third World optimism. I am interested in thinking particuarly on economic and political sovereignty, and raise questions as to how the global political economy has developed following the Cold War, particularly as to what visions or hegemonic ideas still persist in how countries are able to develop and chart their own paths.

## Notes on data

My data, which are the `.csv` files in `/data`, is almost directly taken from Bevins's figures. But since my visualization was on change over time, made easier by being able to identify same political actors in 1960 and 2018, I had to make 2 decisions that made my data differ from the original that I should note, especially as they brush over important political formations and fights that are historically central to thinking about how the Cold War developed as it did. First, the USSR in 1960 is compared to Russia in 2018. Second, Vietnam's 1960 nominal GDP / capita is an average of North Vietnam's figure ($70) and South Vietnam's ($110). You'll notice that the original figure makes this distinction, but my visualization collapses it into just one number.

On the measurement of economic output, which I took from Bevin's figures, note that: this GDP is nominal (not accounting for inflation) and per capita (accounting for, for example, both China and India having more than triple the population of US in thinking about economic output)

## Dependencies
`pip install wheel`

`pip install pandas`

`pip install plotnine`

## Visualizations

This [tutorial](https://plotnine.readthedocs.io/en/stable/generated/plotnine.geoms.geom_segment.html) was especially helpful to me. 

I worked to visualize the changes in the following, which are saved in the `/viz` folder.

*1. Population rank*

![alt text](/viz/png/1-population-rank-1.png "Title")
&nbsp;
&nbsp;

*2. Nominal GDP / capita rank*

![alt text](/viz/png/2-gdp-rank-1.png "Title")

We see here preservations of economic output among 1st-World-aligned countries at the top of the rankings...

&nbsp;
&nbsp;

*3. Nominal GDP / capita in USD*

...but only when we get to the next figure do we see the _scale_ of this global inequality, and the widening gap that clearly demarcates these countries of the Western and Western-aligned bloc from the countries in purple, which can for general intents and purposes be understood as the Global South.

![alt text](/viz/png/3-gdp-data-8-1.png "Title")

#3: I experimented 2 modifications, which you can also find in the `/viz` folder: one of size of figure, one of how to label.