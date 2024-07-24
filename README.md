# Sleeper Fantasy Football Analysis

This Jupyter Notebook is designed to interact with the Sleeper Fantasy Football API to extract, clean, and analyze fantasy football league data. The project demonstrates my skills in data analysis, API integration, and visualization using Python.

## Features

- **API Data Extraction:** Uses the Sleeper API to gather data from multiple fantasy football leagues.
- **Web Scraping:** Uses pandas read_html to copy a fantasy football stats table from pro-football-reference.com into a dataframe and csv.
- **Data Cleaning:** Processes raw JSON data into structured pandas DataFrames, ensuring data privacy and clarity.
- **Data Manipulation:** Uses pandas to make the dataframe usable for analysis and uses joins, groupby, etc. to analyze the data.
- **Visualization:** Employs `matplotlib` and `seaborn` to create insightful visualizations of league data.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `requests`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sleeper-fantasy-football.git
   ```
2. Navigate to the project directory:
   ```bash
   cd sleeper-fantasy-football
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook sleeper.ipynb
   ```

## Usage

1. **Setup League IDs:** Modify the `league_ids` and `seasons` list in the notebook with your specific league IDs and seasons.
2. **Run the Notebook:** Execute the cells to extract and analyze your league data.
3. **Visualize Data:** Review the generated charts and graphs to gain insights into league dynamics.

## Project Structure

- **Data Extraction:** Connects to the Sleeper API and retrieves data for specified leagues.
- **Data Cleaning:** Cleans and structures the data for analysis.
- **Visualization:** Generates plots to visualize league performance and statistics.
- **Analysis:** Provides insights into league standings and player performance.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, please reach out to [email address](mailto:steven.arbo@icloud.com).

---

### Suggestions for Improvement and Future Plans

1. **Visualization Examples:**
   - Include a section showcasing example visualizations and insights derived from the analysis.

2. **Analysis Insights:**
   - Provide a brief overview of any interesting findings or patterns observed in the data.

3. **Project Goals:**
   - Clearly state the objectives and potential applications of the analysis for fantasy football enthusiasts or analysts.
