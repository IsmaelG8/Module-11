# Mars Weather
![Mars](https://github.com/IsmaelG8/Module-11/assets/128990362/aecf2be1-68f5-40ce-9cd1-1537ff6ec95c)

Project Description:

This project represents a comprehensive analysis of Martian climate data, aimed at extracting and visualizing key weather patterns and atmospheric conditions on Mars. Employing advanced web-scraping techniques alongside Python's powerful data analysis and visualization libraries, the project delivers insightful observations about Mars's climate, supporting further scientific exploration and research.

Objective:

The primary objective was to leverage Python, along with libraries such as Splinter for automated web browsing, Beautiful Soup for HTML parsing, Pandas for data manipulation and analysis, and Matplotlib for data visualization, to:

Scrape Mars news articles for titles and preview text.
Scrape and analyze Mars weather data, focusing on temperature and atmospheric pressure across different Martian months.
Technical Approach:

The project was structured into two main parts:

Mars News Web Scraping:

Developed a Jupyter Notebook script (part_1_mars_news.ipynb) to automate the scraping of the Mars News website using Splinter and Beautiful Soup.
Extracted titles and preview texts of news articles, storing each article's details in a list of dictionaries for easy access and manipulation.
Optionally exported the scraped data into a JSON file (mars.json), enhancing data shareability.
Mars Weather Data Scraping and Analysis:

Utilized another Jupyter Notebook script (part_2_mars_weather.ipynb) for scraping Mars weather data from a designated URL using automated web browsing techniques.
Assembled the scraped data into a Pandas DataFrame, aligning with the structure and headings of the original web table, including identification numbers, terrestrial dates, sols (Martian days), solar longitude, Martian months, minimum temperatures, and atmospheric pressure.
Performed data type conversions to ensure accurate datetime, integer, and float representations.
Conducted a comprehensive analysis of the dataset to determine the number of Martian months, the range of Martian days covered, average minimum daily temperatures and atmospheric pressure by month, and an estimation of the number of Earth days in a Martian year.
Visualized the findings through bar charts, providing clear insights into Martian climate patterns.
Outcomes:

The project successfully extracted and analyzed Martian climate data, yielding valuable insights into the seasonal patterns, temperature variations, and atmospheric conditions on Mars. Key findings include the identification of the coldest and warmest months, months with the lowest and highest atmospheric pressure, and an approximation of a Martian year in Earth days. These insights were effectively communicated through detailed visualizations and an organized dataset, exported as mars_data.csv for further use and sharing.

Tools and Technologies Used:

Python: For overall scripting and data analysis.
Splinter and Beautiful Soup: For automated web scraping and HTML parsing.
Pandas: For data manipulation and analysis.
Matplotlib: For generating visualizations of the analyzed data.
Jupyter Notebook: As the development environment for script execution and analysis workflow documentation.
Conclusion:

This project underscores my proficiency in data collection, organization, analysis, and visualization, particularly within the context of planetary science. It demonstrates my ability to leverage web scraping and data analysis tools to extract meaningful insights from complex datasets, making me well-equipped to tackle data-driven challenges in scientific research and beyond.
