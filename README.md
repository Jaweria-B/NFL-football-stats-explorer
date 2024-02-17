# NFL Football Stats (Rushing) Explorer

Welcome to the NFL Football Stats (Rushing) Explorer! This Streamlit app allows you to explore rushing statistics of NFL players from various teams and positions. You can select a specific year, team(s), and position(s) to view player stats and even download the data as a CSV file. Additionally, you can generate an intercorrelation heatmap to explore the relationships between different statistical variables.

<p>
  <img src="./assets/nfl-logo.png" alt="NFL Logo" width="200" height="300">
</p>

## Features

- **Data Source:** The app scrapes data from [Pro Football Reference](https://www.pro-football-reference.com/), focusing on rushing statistics.
- **User Input:** Allows users to select a year, team(s), and position(s) through the sidebar.
- **Data Display:** Displays selected player statistics in a tabular format with dynamic dimensions.
- **Data Download:** Provides an option to download the displayed player statistics as a CSV file.
- **Intercorrelation Heatmap:** Generates an intercorrelation heatmap to visualize relationships between statistical variables.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Jaweria-B/NFL-football-stats-explorer
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

## Demo
[Live Demo](https://nfl-football-stats-explorer-jb.streamlit.app/)

## Usage

1. Upon running the app, you'll be presented with a sidebar containing user input features such as the year, team selection, and position selection.
2. Select the desired options from the sidebar to filter the player statistics.
3. The app will display the selected player statistics in a tabular format.
4. You can download the displayed data as a CSV file by clicking the "Download CSV File" link.
5. To explore relationships between statistical variables, click the "Intercorrelation Heatmap" button to generate and visualize the intercorrelation heatmap.

## Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Base64

## Credits

- Data source: [Pro Football Reference](https://www.pro-football-reference.com/)
