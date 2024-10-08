
# QuantumInvest

QuantumInvest is a Python-based financial decision-making tool designed for sequential investment of assets in Stocks, Gold, and Bonds. The tool helps optimize investment decisions on a weekly basis by utilizing historical data, linear regression models, and decision-making algorithms with MiniZinc.

## Project Overview

In this project, you work within the Finance Department of a company, tasked with identifying the best investment opportunities each week. You can allocate funds to Stocks, Gold, and Bonds, each of which comes with specific constraints. The primary goal is to maximize overall income by making optimal decisions regarding how to distribute available capital among these assets.

## Features

- **Data Preprocessing:** Handles extraction and preparation of time series data related to stock prices and gold values.
- **Linear Regression Models:** Predicts future market trends using linear regression based on historical data.
- **Decision-Making Algorithm:** Uses a linear programming model with MiniZinc to determine the best investment decisions.
- **Sequential Investment Analysis:** Simulates and visualizes the weekly investment process, including returns and decisions made over time.
- **Customizable Initial Capital:** Allows users to set an initial amount of capital and track its growth or decline throughout the investment period.
- **Result Visualization:** Provides detailed output of investment performance, including the value of each asset and the overall portfolio at each stage.

## Technologies Used

- **Python:** The core programming language used for implementing data processing, model development, and decision-making algorithms.
- **Pandas:** A Python library for data manipulation and analysis, particularly useful for handling time series data.
- **NumPy:** A library for numerical computing in Python, used for efficient array operations and mathematical calculations.
- **Matplotlib:** A Python plotting library used to create visualizations of the investment performance and decision-making process.
- **MiniZinc:** A constraint modeling language used for implementing the decision-making algorithm based on linear programming.
- **MiniZinc Python API:** Facilitates the integration of Python scripts with MiniZinc models for seamless decision-making processes.

## Installation

QuantumInvest requires Python and specific libraries for data processing, model development, and decision-making. Additionally, MiniZinc is used for implementing the decision-making algorithms. Ensure that all necessary tools and libraries are installed and configured.

### Additional Dependencies

The project requires MiniZinc and its Python API to integrate the decision-making model with the linear regression forecasts. Proper installation and configuration of MiniZinc are essential for the project's success.

## Usage

1. **Data Collection:** Obtain historical data for stock and gold prices. Ensure that the data is properly formatted and compatible with the tool.
2. **Configuration:** Set initial capital and any other parameters in the configuration file according to the specific needs of the investment strategy.
3. **Execution:** Run the model to generate weekly investment decisions and review the output, which includes detailed performance metrics for each asset and the overall portfolio.
4. **Visualization:** Analyze the results through visual outputs, including charts that illustrate the decision-making process over time.

## Project Structure

- **`data/`**: Contains input data files required for running the model.
- **`models/`**: Includes the linear regression models and decision-making algorithms.
- **`scripts/`**: Consists of Python scripts used for data preprocessing, model training, and decision-making.
- **`results/`**: Stores the output files and visualizations generated by the program.
- **`main.py`**: The main script that orchestrates the entire decision-making process.

## Reporting

The project should be accompanied by a comprehensive report that documents all strategies and code. The report should cover:

- Implementation steps taken during the project.
- Analysis of results, including performance metrics and runtime statistics.
- A Gantt chart illustrating the decision-making process over time.

## References

- Resources and tutorials for understanding linear regression with time series data and MiniZinc.
- Documentation and guidelines for setting up the necessary tools and libraries.

## License

This project is licensed under the MIT License. Please refer to the LICENSE file for detailed information.
