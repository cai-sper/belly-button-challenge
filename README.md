# Interactive Web Visualizations

This project showcases interactive web visualizations using D3, Plotly, and JavaScript to explore the **Belly Button Biodiversity dataset**. This dataset catalogs the microbes that colonize human navels, revealing that a small handful of microbial species, also called operational taxonomic units (OTUs), were present in more than 70% of people, while the rest were relatively rare.

## Table of Contents
1. [Getting Started](#getting-started)
2. [Visualizations](#visualizations)
   - [Bar Chart](#bar-chart)
   - [Bubble Chart](#bubble-chart)
   - [Demographic Panel](#demographic-panel)
3. [Usage](#usage)

## Getting Started

To explore the Belly Button Biodiversity dataset through interactive web visualizations, follow these steps:

1. Open the web page containing the visualizations at [https://cai-sper.github.io/belly-button-challenge/](https://cai-sper.github.io/belly-button-challenge/).
2. Use the dropdown menu to select a sample by its ID.

## Visualizations

### Bar Chart

The **Bar Chart** displays the top 10 operational taxonomic units (OTUs) found in the selected individual's navel. It utilizes the following data:

- **Values**: Sample values are used for the bar chart, indicating the abundance of each OTU.
- **Labels**: OTU IDs are employed as labels for the bar chart, identifying each specific OTU.
- **Hovertext**: OTU labels are displayed as hovertext, providing additional information when users interact with the chart.

### Bubble Chart

The **Bubble Chart** provides a graphical representation of OTU data for the selected individual. When interpreting the Bubble Chart:

- **X Values**: OTU IDs are plotted on the x-axis.
- **Y Values**: Sample values are plotted on the y-axis, representing the abundance of OTUs.
- **Marker Size**: The size of each marker corresponds to the abundance of the respective OTU, with larger markers indicating higher abundance.
- **Marker Colors**: OTU IDs determine marker colors, allowing you to distinguish between different OTUs.
- **Text Values**: OTU labels are displayed as text values, providing information about each data point.

### Demographic Panel

The **Demographic Panel** presents metadata for the selected individual, providing additional context. It displays key-value pairs from the metadata JSON object, offering demographic information about the individual.

## Usage

Explore the interactive web visualizations to gain insights into the microbial diversity of human navels. Select different samples using the dropdown menu to update the plots and discover unique patterns in the data.
