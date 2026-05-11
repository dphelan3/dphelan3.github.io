---
layout: page
title: "Mapping Crime in Chicago"
---

# Mapping Crime in Chicago: What Public Data Shows About the City

By Daniel Phelan

This project explores crime data from the City of Chicago’s public “Crimes - 2001 to Present” dataset. Each record represents a reported crime, including details such as the type of crime, date, location, and whether an arrest was made. Because the full dataset is very large, I used a sample of 100,000 rows to make the data easier to analyze and visualize.

## Most Common Crime Types
<div id="top-crimes-chart"></div>

<script src="https://cdn.jsdelivr.net/npm/vega@5"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-lite@5"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-embed@6"></script>

<script>
  vegaEmbed("#top-crimes-chart", "/assets/json/top_crimes.json");
</script>
This chart shows the most common crime types in the dataset. It helps give a basic understanding of what kinds of incidents happen most frequently before looking at more detailed patterns in the data.
