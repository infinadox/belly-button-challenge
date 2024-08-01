# Belly Button Biodiversity

This project creates an interactive dashboard to explore the Belly Button Biodiversity dataset. The dashboard includes a horizontal bar chart, a bubble chart, and a panel displaying metadata for each sample. Users can select different samples from a dropdown menu to update the charts and metadata dynamically.

## Project Structure

- `index.html`: The main HTML file containing the structure of the dashboard.
- `app.js`: The JavaScript file with the code to fetch data, create charts, and handle user interactions.
- `samples.json`: The JSON file containing the dataset used for the visualizations.

## Features

- **Horizontal Bar Chart**: Displays the top 10 OTUs found in the selected individual. Uses `sample_values` for the bar chart values, `otu_ids` for the labels, and `otu_labels` for the hover text.
- **Bubble Chart**: Displays each sample with `otu_ids` on the x-axis, `sample_values` on the y-axis, marker size based on `sample_values`, and marker colors based on `otu_ids`. Hover text shows `otu_labels`.
- **Metadata Panel**: Displays demographic information for the selected individual.

## Instructions

1. Clone the repository:
    ```sh
    git clone https://github.com/infinadox/belly-button-challenge.git
    ```
2. Navigate to the project directory:
    ```sh
    cd belly-button-biodiversity
    ```
3. Open `index.html` in your browser to view the dashboard.

## Deployment

The dashboard is deployed using GitHub Pages. You can view the live app [here](https://infinadox.github.io/belly-button-challenge/).

## Usage

- Select a sample from the dropdown menu to update the charts and metadata panel.
- Hover over the bars in the bar chart and the markers in the bubble chart to view additional information.

## Troubleshooting

- Make sure you have an internet connection as the project fetches data from a remote URL.
- Use `console.log` in `app.js` to debug and inspect data at various stages of processing.

## License

This project is licensed under the MIT License.

## Acknowledgements

- The dataset is provided by the [Belly Button Biodiversity project](https://robdunnlab.com/projects/belly-button-biodiversity/).
- The project uses [D3.js](https://d3js.org/) and [Plotly.js](https://plotly.com/javascript/) for data visualization.


