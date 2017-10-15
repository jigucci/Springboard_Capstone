---
layout: "post"
title: "Capstone Project Proposal"
date: "2017-10-08 00:37"
---

#### 1. What is the problem you want to solve?

  According to a WHO assessment of the burden of disease due to air pollution, more than 2 million premature deaths each year can be attributed to the effects of urban outdoor
  air pollution and indoor air pollution (caused by the burning of solid fuels). The evidence on airborne particulate matter (PM) and its public health impact is consistent in showing adverse health effects at exposures that are currently experienced by urban populations in both developed and developing countries. Shanghai, the commercial capital city of People's Republic of China, is no exception in exceeding the healthy levels of pollution due to the impact of urbanization, motorization, and rapid population growth. In this report, we would like to use several years of meteorological and pollution data to predict the concentrations of PM2.5 (ug/m3).

#### 2. Who is your client and why do they care about this problem? In other words, what will your client DO or DECIDE based on your analysis that they wouldn’t have otherwise?

  My client is the residents in Shanghai, P.R. China and the members serving in the city council. Outdoor air pollution is a major environmental health problem. Particulate matter (PM) is one of the major indicators of air quality proposed by WHO. PM affects more people other than any other pollutant. PM2.5 concentration (ug/m3) are the concentration of PM with a diameter of 2.510 microns or less. (<=PM2.5). The residents can benefit from the following analysis:

  - A prediction model for PM2.5 based on the dependent variables can help the residents make decision of going outside or not in case they don’t have other constraints.
  - The relationship between PM2.5 concentration and time related information can help members of the city council as well as citizens understand the trending and pattern of PM2.5 concentration and thus assist in their decision making and efforts to improve air quality.

#### 3. What data are you going to use for this? How will you acquire this data?

  The hourly data set contains the PM2.5 data in Beijing, Shanghai, Guangzhou, Chengdu and Shenyang. Meanwhile, meteorological data for each city are also included. But the dataset for Shanghai will be used for this capstone project. The location to download the dataset is as follows:
    https://archive.ics.uci.edu/ml/datasets/PM2.5+Data+of+Five+Chinese+Cities

#### 4. In brief, outline your approach to solving this problem (knowing that this might change later).
  - Compare the PM2.5 measured at the three locations and analyze the correlations between them.

  - Derive final PM2.5 concentration values to be used as dependent variables.

  - Data cleaning (e.g. impute missing data)

  - Explore the relationship between the dependent variables and independent variables. Some
    examples such as:

    - Explore the relationship between time stamp (season, month, hour etc.) and PM2.5   
      concentration
    - Explore the relationship between wind characteristics (combined wind direction,
      cumulated wind speed) and PM2.5 concentration.


  - Predict PM2.5 value based on the dependent variables.

    - Data Wrangling
    - Data Visualization
    - Predictive analytics (Regression modeling)

#### 5. What are your deliverables? Typically, this would include code, along with a paper and/or a slide deck.

  - Python code (with comments)
  - PDF report
  - Presentation
