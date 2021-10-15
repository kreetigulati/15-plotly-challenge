# Belly Button Biodiversity with Plotly

![Bacteria by filterforge.com](Images/bacteria.jpg)

In this assignment, we will build an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Summary
  * Using the provided data on Belly Button Biodiversity, our goal is to create and interactive dashboard using HTML/CSS, Plotly, and D3. The purpose of the interactive dashboard is to provide the scientist the ability to read through the data quickly to find the answers they are searching. 
  * The first step was create link to the JavaScript files to the HTML page and ensure that the bubble chart and bar chart update as the dropdown menu and demogrpahic information udpates for each specific OTU selected.

## Step 1: Plotly

1. Use the D3 library to read in `samples.json`.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

* Use `sample_values` as the values for the bar chart.

* Use `otu_ids` as the labels for the bar chart.

* Use `otu_labels` as the hovertext for the chart.

  ![bar Chart](https://github.com/kreetigulati/15-plotly-challenge/blob/main/Images/barchart.png)

3. Create a bubble chart that displays each sample.

* Use `otu_ids` for the x values.

* Use `sample_values` for the y values.

* Use `sample_values` for the marker size.

* Use `otu_ids` for the marker colors.

* Use `otu_labels` for the text values.

![Bubble Chart](https://github.com/kreetigulati/15-plotly-challenge/blob/main/Images/matchingbubblechart.png)

4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

![hw](https://github.com/kreetigulati/15-plotly-challenge/blob/main/Images/updatedropdowninfo.png)

6. Update all of the plots any time that a new sample is selected.


## Deployment

* Link to live, static webpage: https://kreetigulati.github.io/(https://kreetigulati.github.io/)


### About the Data

Hulcr, J. et al.(2012) _A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable_. Retrieved from: [http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)
