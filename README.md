# ufo_sightings
A brief analysis of the UFO sightings dataset is presented in the pdf file as a presentation.
It uses data exploration, Natural Language Processing (NLP) and Time Series methods.

Part 1 of the R markdown code explores the dataset, creates the time series object monthly_ts.rda for Part 2 and uses NLP to find the top 10 descriptions used in the comments.

Part 2 of the R markdown code uses  monthly_ts.rda as the input data object (created in Part 1) and models the time series for a forecast of number of monthly sightings.

The source data is provided in ufo.csv, a modified version of the original dataset from https://www.kaggle.com/NUFORC/ufo-sightings/home
