# Project Title
**SP500 Closing Price Analysis (2019-2024)**

This project focuses on analyzing the SP500 index's closing prices from 2019 to 2024. It provides statistical insights such as the maximum, minimum, average, standard deviation, and other key metrics to help investors track the performance of the index. Users can select specific analyses via a menu and save results to an output file.

---

## Motivation
The SP500 index is a critical benchmark for evaluating the overall performance of the stock market. Understanding the historical movements of its closing prices can provide insights into market trends and help make more informed investment decisions. This project is designed to offer a set of essential analysis tools to better understand the SP500 index's price fluctuations and overall volatility.

---

## Build Status
The current version of the project is **fully functional**. The program runs successfully, providing options to calculate different statistics for SP500 closing prices. All features have been tested, and no known bugs exist at this time.

---

## Code Style
The code is written in **standard Python 3.x** style. It follows PEP8 guidelines to ensure readability and maintainability.

---

## Screenshots
_No screenshots included in this project._ (If applicable, you could include a screenshot here showing the program running or example output.)

---

## Tech/Framework Used
- **Python 3.x**
  - Standard Python libraries such as `csv` for file handling.
  
---

## Features
This project offers the following features:
- **Maximum and Minimum Closing Price**: Analyze the highest and lowest SP500 closing prices.
- **Average and Median Closing Price**: Understand central tendencies in the data.
- **Standard Deviation**: Measure the volatility of the closing prices.
- **Highest Daily Percentage Increase**: Identify the day with the largest percentage gain.
- **Total Percentage Change**: Calculate the overall change in SP500 from the start to the end of the dataset.
- **Daily Volatility**: Understand average daily price swings.

---
## Code Examples

Here’s a code snippet from the project that calculates the maximum closing price:

```python
def manualMax(prices):
    max_val = prices[0]
    for price in prices:
        if price > max_val:
            max_val = price
    return max_val
```
---
 ## Installation

To install and run the SP500 Closing Price Analysis project, follow these steps:

1. **Open the Colab or Python 3.x version by the link**

  https://colab.research.google.com/drive/1SJEtS959kGB_mU14BGj3DTyRmcSoL6uN?usp=sharing

2. **Download the dataset of SP500**
3. **Operate 
