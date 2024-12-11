# Belly Button Biodiversity Dashboard

This project creates an interactive dashboard for exploring belly button biodiversity data. The application visualizes microbiome data using bar and bubble charts, along with a demographic information panel. It dynamically updates based on user input.

## Instructions

Complete the following steps:

1. **Use D3 Library**  
   Read the `samples.json` file from the URL:  
   `https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json`.

2. **Horizontal Bar Chart**  
   - Create a horizontal bar chart to display the top 10 OTUs found for each individual.  
   - Use `sample_values` as the bar chart values.  
   - Use `otu_ids` as the labels for the bar chart.  
   - Use `otu_labels` as the hovertext for the chart.

3. **Bubble Chart**  
   - Create a bubble chart to display all OTUs for each sample.  
   - Use `otu_ids` for the x-axis values.  
   - Use `sample_values` for the y-axis values.  
   - Use `sample_values` to set the marker size.  
   - Use `otu_ids` to set the marker colors.  
   - Use `otu_labels` for the text values.

4. **Metadata Panel**  
   - Display demographic information for the selected individual.  
   - Loop through the metadata JSON object and display key-value pairs.  
   - Append the metadata to the `#sample-metadata` panel.

5. **Dynamic Updates**  
   - Update all visualizations and the metadata panel when a new sample is selected using the dropdown menu.

6. **Deployment**  
   - Deploy the application to a free static hosting service, such as GitHub Pages.  
   - Submit links to both the deployed app and the GitHub repository.

---

## Hints

- Use `console.log()` to debug and view your data at various steps.
- Refer to the [Plotly.js documentation](https://plotly.com/javascript/) for help building the plots.
