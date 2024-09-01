

# UNSW-NB15 Cybersecurity Data Analysis

This repository contains the code for performing exploratory data analysis (EDA) and statistical analysis on the UNSW-NB15 dataset. The UNSW-NB15 dataset is a widely used dataset in cybersecurity research, providing a comprehensive set of features for analyzing various types of network traffic and attacks.

## Table of Contents

- [Dataset](#dataset)
- [Installation](#installation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Descriptive Statistics](#descriptive-statistics)
  - [Chi-Square Test for Categorical Variables](#chi-square-test-for-categorical-variables)
  - [T-Test for Continuous Variables](#t-test-for-continuous-variables)
- [Visualizations](#visualizations)
  - [Attack Category Distribution](#attack-category-distribution)
  - [Source IP Distribution](#source-ip-distribution)
  - [Connection State Distribution](#connection-state-distribution)
  - [Connection Duration Distribution](#connection-duration-distribution)
  - [Source and Destination Bytes](#source-and-destination-bytes)
  - [Source and Destination Packets](#source-and-destination-packets)
  - [Correlation Matrix](#correlation-matrix)
  - [TTL Distribution](#ttl-distribution)
  - [Jitter Analysis](#jitter-analysis)
  - [Inter-Packet Time](#inter-packet-time)
  - [Bytes by Attack Category](#bytes-by-attack-category)
  - [Connection Duration by Attack Category](#connection-duration-by-attack-category)
  - [Attack Categories by Protocol](#attack-categories-by-protocol)
  - [Categorical Feature Analysis](#categorical-feature-analysis)
  - [Source and Destination TCP Window Advertisement](#source-and-destination-tcp-window-advertisement)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Dataset

The dataset used in this project is the UNSW-NB15 dataset, which includes labeled network traffic data with a wide variety of features. The data is categorized into several attack types, as well as normal traffic. The dataset is split into four CSV files, which are combined into a single DataFrame for analysis.

## Installation

To run this project, you will need the following Python libraries:

```bash
pip install pandas numpy seaborn matplotlib scipy
```

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/saadnaveeddev/unsw-nb15-analysis.git
cd unsw-nb15-analysis
```


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue for any bug fixes, enhancements, or suggestions.

## License

This project is licensed under the MIT License 

## Contact

For any inquiries, please reach out to Saad Naveed at saad.naveed.dev@gmail.com.

