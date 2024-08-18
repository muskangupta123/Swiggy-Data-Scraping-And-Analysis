# Swiggy-Data-Scraping-And-Analysis

## Overview
This repository contains the code and datasets used for a data-driven analysis of Swiggy's delivery operations. The project explores key aspects such as cuisine preferences, rating distribution, and delivery times to uncover insights that can help improve service efficiency and customer satisfaction.

## Project Structure
- `datasets/`: Contains the datasets used for analysis, including the scraped data.
- `scraping/`: Contains the scripts used for scraping data from Swiggy's website.
- `notebooks/`: Jupyter notebooks containing the analysis and visualizations.
- `README.md`: Project documentation.

## Getting Started

### Prerequisites
- Python 3.8 or higher
- [Google Chrome](https://www.google.com/chrome/) and [ChromeDriver](https://sites.google.com/chromium.org/driver/)
- Python packages:
  - `pandas`
  - `numpy`
  - `requests`
  - `beautifulsoup4`
  - `selenium`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

### Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/swiggy-delivery-analysis.git
   cd swiggy-delivery-analysis
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up ChromeDriver:**
   - Download ChromeDriver from [here](https://sites.google.com/chromium.org/driver/).
   - Place it in your system’s PATH or specify its path in the Selenium script.

### Data Scraping
The `scraping/` directory contains the script used to scrape restaurant data from Swiggy. This script leverages `BeautifulSoup` and `Selenium` for handling static and dynamic content, respectively.

**Usage:**
1. Ensure ChromeDriver is correctly set up.
2. Run the scraping script:
   ```bash
   python scraping/swiggy_scrape.py
   ```
3. The scraped data will be saved in the `datasets/` directory.

### Data Analysis
The analysis is performed using Jupyter notebooks located in the `notebooks/` directory. The key aspects explored include:
- **Cuisine Analysis:** Identifying popular food choices among customers.
- **Rating Distribution:** Understanding customer satisfaction based on restaurant ratings.
- **Delivery Time Analysis:** Evaluating the efficiency of the delivery service and its impact on ratings.

**Usage:**
1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open and run the notebooks located in the `notebooks/` directory.

### Results
The analysis revealed insights such as:
- Popular cuisines on Swiggy.
- Distribution of ratings and identification of outliers.
- Correlation between delivery time and customer ratings.

## Conclusion
This project highlights the power of data analysis in optimizing food delivery services. By understanding customer preferences and service dynamics, platforms like Swiggy can enhance customer satisfaction and operational efficiency.

## Future Work
- Investigating seasonal trends and customer segmentation.
- Incorporating additional features like weather conditions and promotional offers into the analysis.
- Exploring advanced modeling techniques to improve prediction accuracy.

## Contributing
Contributions are welcome! Please feel free to fork this repository and submit pull requests.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.
