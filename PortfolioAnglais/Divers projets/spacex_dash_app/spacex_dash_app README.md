# SpaceX Launch Records Dashboard

This project is an interactive dashboard using the Dash library to display information about SpaceX launches. The data is read from a CSV file and presented in the form of pie charts and interactive scatter plots.

## Project Structure

- `spacex_launch_dash.csv`: This is the data file that contains information about SpaceX launches.

- `main.py`: This is the main script that creates the Dash application and defines the callbacks for user interactions.

## Workflow

1. The Dash application starts by reading the SpaceX launch data from the CSV file.

2. A user interface is created with a header, a dropdown menu to select the launch site, a pie chart to display the total number of successful launches by site, a slider to select a range of payload values, and a scatter plot to show the correlation between payload and success.

3. Two callbacks are defined to update the charts based on user interactions with the dropdown menu and the slider.

## How to Use

To run the application, make sure that all the required files are present in the same directory and run the following command in your terminal:

```
python main.py
```

The application will be accessible in your browser at `localhost:8050`.

**Note:** This dashboard assumes that you have already installed the necessary Python packages, including pandas, dash, dash_core_components, dash_html_components, and plotly.
