# Observations

Data Overview:
• The dataset contains no duplicate entries, but there are approximately 1,246 missing values. The columns 
with missing values include location (5 missing entries), alert, continent, and country, with the latter 
three having hundreds of missing values.
 Magnitude Observations:
• Earthquakes with a magnitude of 6.5 have been recorded most frequently, followed by magnitudes of 
6.6, 6.7, 6.8, 6.9, 7.0, and so on.
 Depth and Significance:
• Most earthquakes occurred at depths below 100 kilometers, with the median depth being around 30 
kilometers.
• In terms of significance, most events have a significance level below 1,000, with the median around 700.
 Correlation Analysis:
• No strong correlation was observed between earthquake magnitude and depth, or between magnitude 
and tsunami occurrence.
• However, there appears to be a moderate correlation between earthquake magnitude and significance.
 Magnitude Measurement Types:
• The Mww (Moment W-phase method) is the most widely used type of magnitude measurement, 
accounting for about 60% of recorded events.
• Other major methods include Mwc (centroid moment tensor method) and Mwb (body wave method), 
representing 28% and 9% of events, respectively.
 Geographic Distribution:
• Around 39% of earthquakes occurred in oceanic areas, while 61% occurred on land.
• The Mww method is predominantly used for oceanic quakes, whereas the Mwc method is commonly 
used for land-based quakes.
 Yearly and Monthly Trends:
• The number of earthquake events was notably high in the years 2013, 2014, and 2015.
• November emerged as the month with the highest occurrence of earthquakes.
 Hourly Distribution:
• Earthquakes are least likely to occur between 4 a.m. and 5 a.m., and most likely to occur between 9 p.m. 
and 10 p.m.
 Missing Data Handling:
• Of the 782 records, 298 were missing country names, while 5 were missing location data.
• To resolve this, a new dataframe was created by extracting the country name from the location field. The 
missing country names were then filled using this information.
• Following this, all missing country data was resolved.
• However, further refinement of the country column was necessary due to inconsistencies like extra spaces 
and varying labels for the same country. For instance, "Fiji" appeared in four forms: 'Fiji', 'the Fiji 
Islands', ' Fiji', and 'Fiji region', all of which were consolidated into a single label.
• Similarly, names like "United States of America" and "United Kingdom of Great Britain and Northern 
Ireland" were shortened to "USA" and "UK" respectively, while remote island territories were retained 
in their original form.
 Top 3 Earthquake-Prone Countries:
• Indonesia: Recorded at least one earthquake with a magnitude of 6.5 or higher every year from 2001 to 
2022. The majority of these were non-tsunami earthquakes (around 90%), with 2007 being a particularly 
active year (13 recorded quakes).
• Japan: Most earthquakes occurred in 2011, including the Fukushima quake. Around 25% of Japan’s 
earthquakes were associated with tsunamis.
• Papua New Guinea: Over 51% of earthquakes in Papua New Guinea were tsunami-related, but no quakes 
above magnitude 8 have been recorded so far.
 General Findings:
• Most earthquakes occurred in coastal regions or oceanic areas, particularly in the Pacific Ocean and 
surrounding regions.
• In contrast, fewer earthquakes were recorded in interior regions away from the coasts.

