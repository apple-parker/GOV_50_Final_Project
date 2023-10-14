---
title: "Gov 50 Final Project"
author: "Adelaide Parker"
description: "Final project for GOV 50"
output:
  distill::distill_article:
    self_contained: false
---



## Project thoughts

I am interested in election analytics and data journalism. Last fall, I took a journalism class where I reported on Utah's 2022 Senate race. I think it would be interesting to analyze this same election using the quantitative data analysis methods we are learning in GOV 50. I'd like to see what new insights I gain when approaching this election from a quantitative vs. a qualitative point of view.


## Data Source and Research Question
How did the absence of a Democratic candidate in Utah's 2022 Senate elections impact Democrats' performances in local Utah races? I hypothesize that it increased Democratic success in local races, because the absence of a Democrat in the 2022 Senate elections (Republican Senator Mike Lee's opponent was instead Independent Evan McMullin) resulted in a much more competitive race than is typical for Utah, attracting greater-than-average media attention and boosting democratic turnout. I will look into this by comparing the success of Utah democrats in local races in 2022, compared with past elections (data from: https://vote.utah.gov/historical-election-results/). I may also compare Utah democrats' success in 2022 to the success of other local Democrats in similarly red states in 2022, to solve for confounding variables that may be specific to that year. My explanatory variable of interest is the presence of a Democrat in each election cycle's highest-profile race (so presidential races in national eleciton years, and Senate races in non-national eleciton years). I will measure the presence of a Democrat as "1", and the absence of a Democrat as "0". My outcome variable of interest is Democrats' performances in local Utah races, measured by the proportion of votes that Democrats recieve within each race. I will try and aggregate this to a statewide level, so I can compare Democratic success in 2022 vs. in prior years. An observed pattern of increased support for local Democrats in 2022 would support my hypothesis; a lack of increased support for local Democrats in 2022 would disprove my hypothesis.
```{.r .distill-force-highlighting-css}
```