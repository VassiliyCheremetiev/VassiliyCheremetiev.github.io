---
layout: page
title: The hidden ecological impact of beer consumption
subtitle: A study of the evolution of the distance bewteen the place of production and the place of consumption
---

## Introduction

Have you ever paid attention to where the beers you drink come from? In this period of ecological awareness, we heavily favours taking the public transportation over a private car, pay attention to the origin of the food we buy, and so on. However, this trend doesn't seem to have any impact on beers. For example, out of the 74 beers available at EPFL's Satellite, only 19 come from Switzerland. In this datastory, we are going to take you on a journey to find out wether we actually do not care where our beers come from.

TALK ABOUT ASSUMPTIONS

As most of the users are from the USA and their locations statewise, we decided to study only this country to make our analysis as pertinent as possible. We will begin by justifying this choice by presenting the countrywise distribution of review. Then, we will look into the evolution of the distance between the place of brewing and of consumption over time. With the idea to explain this evolution, we will try to correlate it with the evolution of the number of breweries per American State and with evolution of the Americans' attitude about climate change. Finally, we will draw the conclusions based on our data analysis.

### Brief overview to the data

Our data consists of metadata about users, beers, breweries, including textual reviews and ratings of beers. They are coming from two website, BeerAdvocate and RateBeer and span over the period 2001 - 2017.

INSERT NICE ICONS AND NUMBERS FOR BOTH DATASETS

The datasets can be found by following [this link](https://drive.google.com/drive/folders/1Wz6D2FM25ydFw_-41I9uTwG9uNsN4TCF).


## Datastory

### Focusing on the USA

Before starting the analysis, we had to find a relevant way to answer our research questions. Many countries having only a handful reviews, we decided to focus on the one providing us the most: the USA. Another interesting point about the USA is that it is split statewise, which provide us much more detail about the internal consumption and allows us to be more precise.

ADD NUMBERS IN THE TEXT
INSERT WORLWIDE DISTRIBUTION OF REVIEWS

This overwhelming majority of american users can also be found in the breweries: most of them are American.

ADD NUMBERS IN THE TEXT
INSERT WORLWIDE DISTRIBUTION OF BREWERIES

### Distance between brewing's and drinking's place

We begun by taking a statewise distribution of the reviews. We then separated all reviews into three categories:
- Local reviews: reviews about a beer originating from the same state
- National reviews: reviews about an american beer from a different state
- Foreign reviews: reviews about beers coming from outside of the USA

INSERT PLOT AND TALK ABOUT IT

As we can see on the plot, California is the only state with more local than national reviews. All other states have a majority of national reviews with small portions of local and foreign ones. However, what interests us is the evolution over time of this distribution. After normalizing the monthly reviews' counts, we get these results:

INSERT PLOT

We can see an almost perfect linear diminution of the foreign review portion (INSERT ACTUAL VALUES), and a relatively stable local reviews' portion followed by a stable augmentation starting in (INSERT MONTH).

INSERT PLOT

The average distance is also following this trend, with a tendency to be reduced with time. We can see two large outliers: Alaska and Hawaï. This is no suprise, as they are quite far away from all other american state and the beers would have to travel a long distance from the continental USA to reach them.


### Evolution of breweries' number


### Effect of climate change attitude


### Conclusion