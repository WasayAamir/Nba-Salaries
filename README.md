# NBA Player Salary Comparison Project

## Overview

This GitHub repository contains a Python-based data analysis project that focuses on comparing NBA player salaries with their Points Per Game (PPG), Position, and Minutes Played (MP). The purpose of this project is to provide insights into the relationship between these key player statistics and their corresponding salaries.

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Data Sources](#data-sources)
4. [Project Structure](#project-structure)
5. [Dependencies](#dependencies)
6. [Usage](#usage)
7. [Analysis](#analysis)
8. [Results](#results)
9. [Contributing](#contributing)
10. [License](#license)

## Introduction

The NBA Player Salary Comparison project aims to explore and visualize the correlation between NBA player salaries, Points Per Game, Position, and Minutes Played. By analyzing these factors, users can gain insights into the financial dynamics of the NBA and better understand how player performance metrics influence salaries.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/nba-salary-comparison.git
## Data Sources

The project utilizes NBA player data and salary information from reputable sources. The primary dataset includes player statistics such as PPG, Position, and MP, along with their corresponding salaries.

- NBA Player Statistics: [NBA API](https://www.nba.com/stats/)
- NBA Player Salaries: [nba_salaries.csv](data/nba_salaries.csv)
  ## Project Structure

  This project is organized as follows
  nba-salary-comparison/
│
├── data/
│   ├── player_stats.csv
│   └── player_salaries.csv
│
├── src/
│   ├── data_preprocessing.py
│   ├── analysis.py
│   └── visualization.py
│
├── notebooks/
│   ├── data_exploration.ipynb
│   └── salary_analysis.ipynb
│
├── results/
│   └── salary_comparison_plot.png
│
├── requirements.txt
├── README.md
└── LICENSE
## Dependencies

- Pandas
- Matplotlib
- Seaborn
- NumPy

Install the required dependencies using the command mentioned in the [Getting Started](#getting-started) section.

## Usage

To run the analysis and generate visualizations, execute the following command:

      ```bash
         python src/analysis.py
...

## Analysis

The analysis script performs the following tasks:

1. Data preprocessing, including merging player statistics and salary data.
2. Exploratory data analysis to understand the distribution of variables.
3. Correlation analysis to determine the relationship between salary, PPG, Position, and MP.

## Results

The main result of the analysis is a visualization that illustrates the relationship between player salaries, Points Per Game, Position, and Minutes Played. The resulting plot is saved in the results directory as `salary_comparison_plot.png`.

![Salary Comparison Plot](results/salary_comparison_plot.png)

## Contributing

Contributions to this project are welcome. If you have ideas for improvements or new features, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as needed.




