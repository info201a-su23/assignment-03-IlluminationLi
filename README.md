# A2: U.S. COVID Trends

## Overview
In many ways, we have come to understand the gravity and trends in the COVID-19 pandemic through data. Regardless of media source, people are consuming more epidemiological information than ever, primarily through reported figures, charts, and maps.

This assignment is your opportunity to work directly with the same data used by the [New York Times](https://github.com/nytimes/covid-19-data/). While the analysis is guided through a series of questions, it is your opportunity to use programming skills to ask more detailed questions about the pandemic.

## Getting Started
You should start this assignment by opening up the `analysis.R` script. The script will guide you through an initial analysis of the data.

* **Coding prompts.** Complete the coding prompts in `analysis.R`. You MUST use the `dplyr` package.

* **Reflection prompts.** Throughout `analysis.R`, there are prompts labeled `"Reflection"`. Please write at least 1-3 sentences for each of these prompts below in this `README.md` file. As appropriate, provide evidence, give justification for your opinions, or genuinely reflect on your views. Please strive for concise, clear, and interesting writing.

## Reflection 1
Before actually calculating the total number of COVID cases and deaths, record your guesses for the following questions.


Guess: How many total COVID cases do you think there have been in the U.S.?

My guess is 5 million in total because a person may get infected twice or even more times.

Guess: How many total COVID-related deaths do you think there have been in the U.S.?

My guess is roughly 50,000 Covid-related deaths in total.

Guess: Which state do you think has the highest number of COVID cases, and which state do you think has the lowest?

Highest number of Covid case state: New York
Lowest number of Covid case state: Oregon

## Reflection 2
Did the number of COVID cases and deaths surprise you? Why or why not? What about the states with the highest and lowest number of cases? How did your guesses line up with the actual results? Answer in at least 1-3 sentences

I was really surprised by the high number of COVID cases and deaths. California had the most cases because it has lots of people living there. I thought another state would have the least cases, but it turned out to be Alaska rather than Oregon. The actual data was different from what I expected.My guess is not exactly the same as what the data shows but it's closed.

## Reflection 3
Which county has the highest number of cases in the state of Washington, and does it surprise you? Why or why not? (You may need to google this county to learn about it) Answer at least in 1-3 sentences

King county (with 410322 cases). Because it's the largest and most populous county in Washington state. This result wasn't surprising, as I expected a county with Seattle's fame and coastal location to have the highest cases. King County has been a COVID-19 hotspot since 2020, with some of the earliest cases reported in the United States.

## Reflection 4
Why are there so many observations (counties) in the variable `lowest_deaths_in_each_state`? That is, wouldn't you expect the number to be around 50? Why is the number greater than 50? Answer in at least 1-3 sentences

Certain states have multiple counties with the same lowest number of COVID-related deaths. The number of observations exceeds the total number of U.S. counties because the dataset includes each county multiple times with different dates but the same death numbers.

## Reflection 5
What do you think about the number and scale of the inconsistencies in the data? Does the fact that there are inconsistencies mean that people should not use this data? Why or why not? Answer in at least 1-3 sentences

It's not surprising to find inconsistencies in COVID data because it's collected on a very large scale, from counties to the entire country. The differences are not significant enough to affect our understanding of the overall COVID trends. By studying the reason of these difference and inconsistencies, we can make the data more reliable for the future. It's common and totally acceptable that data has some errors. Still, this COVID data is useful and gives us valuable insights into the situation.

## Reflection 6
Why were you interested in this particular question? Were you able to answer your question with code? What did you learn? Answer in at least 1-3 sentences

My question asks for the median number of recorded COVID cases at the very beginning date. This is meaningful to me because we all know how disease spread. If we have a large infected population at the beginning, these infected people can cause exponential increase in new cases (just as how cells grow, if we have more cells at T0, then the cell colony will grow much quickly than those with less cells at T0.). Luckily, the median number is 1 at the beginning, whcih means there are lots of things that government can do to control the Pandemic. But if the cases at T0 is much larger, then the pandemics is much severer than we expected.

## Reflection 7
What, if anything, made you curious about this COVID analysis? What, if anything, surprised you? What might you do the same or differently on your next data wrangling project? Answer in at least 1-3 sentences

I'm  curious about the widespread impact of COVID-19 in different U.S. states and the speed at which the Covid spreads across the country. For my next data wrangling project, I would like to dive deep to see if there is any trend in cases and deaths and exploring potential factors such as population, medical conditions, and policies. I'm looking forward to use different function to manipulate the data and to explore the relation or trends of the cases between different periods.
