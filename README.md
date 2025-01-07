# Mars Weather Data Challenge

## Project Overview

This project focuses on scraping, analyzing, and visualizing weather data from the surface of Mars as collected by NASA's Curiosity Rover. The goal of this challenge is to strengthen your web-scraping skills, data analysis abilities, and visualization techniques using Python and associated libraries. 

You will explore the seasonal variations on Mars by analyzing temperature and atmospheric pressure data, estimate the length of a Martian year, and export the cleaned data for further use.

## Deliverables

1. **Deliverable 1**: Scrape titles and preview text from Mars news articles.
2. **Deliverable 2**: Scrape and analyze Mars weather data, including:
   - Identifying the coldest and warmest months on Mars.
   - Identifying the months with the highest and lowest atmospheric pressure.
   - Estimating the length of a Martian year visually.
   - Exporting the cleaned weather data to a CSV file.

## Files Included

- **`part_1_mars_news.ipynb`**: Jupyter Notebook for scraping Mars news article data.
- **`part_2_mars_weather.ipynb`**: Jupyter Notebook for scraping, analyzing, and visualizing Mars weather data.
- **`mars_weather_data.csv`**: Exported CSV file containing the cleaned weather data.

## Technologies Used

- **Python Libraries**:
  - `pandas` for data manipulation and analysis.
  - `matplotlib` for creating visualizations.
  - `BeautifulSoup` for web scraping.
  - `Splinter` for automated browsing.
- **Jupyter Notebook** for interactive data exploration.

## Key Questions Addressed

1. **Which month, on average, has the lowest and highest temperatures?**
   - A bar chart was created to visualize the average minimum temperature for each Martian month.
   - Analysis identified month 3 as the coldest and month 8 as the warmest.

2. **Which month, on average, has the lowest and highest atmospheric pressure?**
   - A bar chart was created to visualize the average atmospheric pressure for each Martian month.
   - Analysis identified month 6 as having the lowest pressure and month 9 as having the highest pressure.

3. **How many terrestrial days exist in a Martian year?**
   - A line chart was created to plot minimum temperatures over time, showing a clear repeating pattern.
   - Visual analysis estimated a Martian year to be approximately 669 sols or ~687 Earth days, within 25% accuracy.

## Setup Instructions

1. Clone this repository to your local machine.
2. Ensure you have Python 3.7 or later installed.
3. Install the required libraries using:
   ```bash
   pip install pandas matplotlib splinter beautifulsoup4
   ```
4. Open the provided Jupyter Notebooks (`part_1_mars_news.ipynb` and `part_2_mars_weather.ipynb`) in Jupyter Notebook or Jupyter Lab.
5. Follow the step-by-step instructions in the notebooks to execute the code.

## Resources Used

- **ChatGPT (AI Assistant)**: Assisted with structuring code, debugging, analyzing data, and formatting this document.
- **Xpert Learning Assistant**: Provided additional support for understanding web scraping and data analysis concepts.
- **BeautifulSoup Documentation**: Used for extracting HTML content.
- **Splinter Documentation**: Assisted with automated browsing and HTML rendering.
- **Pandas Documentation**: Helped with DataFrame manipulations and data cleaning.
- **Matplotlib Documentation**: Used for creating visualizations.
- **Mars Weather Data Source**: [Mars Weather Data Table](https://static.bc-edx.com/data/web/mars_facts/temperature.html).

