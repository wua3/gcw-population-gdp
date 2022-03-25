# Visualizing Global Cold War
Data visualizations created from the figures of Appendix 1 (The World in 1960: The 25 Most Populous Countries) and Appendix 2 (The World Today: The 25 Most Populous Countries (plus South Korea) in 2018) of Vincent Bevin's 2020 book [The Jakarta Method](https://vbpublic.wpcomstaging.com/book/). `/data/scans.pdf` has the original figures, where you can see Bevin's notes on sourcing & any irregularities. My visualizations are meant to highlight shifts and preservations of economic output by country over the last half century, particularly in context of the promises and arguments of the Cold War as a global phenomenom and as a huge part of why our world is organized and exists the way it does today.

## Notes on data

My data, which are the `.csv` files in `/data`, is almost directly taken from Bevin's figures. But since my visualization was on change over time, made easier by being able to identify same political actors in 1960 and 2018, I had to make 2 decisions that made my data differ from the original that I should note, especially as they brush over important political formations and fights that are historically central to thinking about how the Cold War developed as it did. First, the USSR in 1960 is compared to Russia in 2018. Second, Vietnam's 1960 nominal GDP / capita is an average of North Vietnam's figure ($70) and South Vietnam's ($110). You'll notice that the original figure makes this distinction, but my visualization collapses it into just one number.

On the measurement of economic output, which I took from Bevin's figures, note that: this GDP is nominal (not accounting for inflation) and per capita (accounting for, for example, both China and India having more than triple the population of US in thinking about economic output)

## Dependencies
`pip install wheel`

`pip install pandas`

`pip install plotnine`

## Visualizations

This [tutorial](https://plotnine.readthedocs.io/en/stable/generated/plotnine.geoms.geom_segment.html) was especially helpful to me. 

I worked to visualize the changes in the following, which are saved in the `/viz` folder.

1. Population rank

2. Nominal GDP / capita rank

3. Nominal GDP/ capita in USD

#3: I experimented 2 modifications, which you can also find in the `/viz` folder: one of size of figure, one of how to label.