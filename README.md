# Cybersecurity Attack Analysis EDA

## Overview

This project focuses on Exploratory Data Analysis (EDA) of a cybersecurity attack dataset containing 40,000 records and 25 features. The goal is to identify attack patterns, analyze severity levels, understand protocol usage, detect anomalies, and gain insights into network security events.

## Objectives

* Analyze different types of cybersecurity attacks.
* Study attack severity levels and their distribution.
* Explore network traffic behavior and protocol usage.
* Detect anomalies using anomaly scores.
* Identify trends across network segments and log sources.
* Visualize data using statistical and graphical techniques.

## Dataset Information

* **Dataset Name:** Cybersecurity Attack Dataset
* **Records:** 40,000
* **Features:** 25
* **Format:** CSV

### Key Columns

* Timestamp
* Source IP Address
* Destination IP Address
* Source Port
* Destination Port
* Protocol
* Packet Length
* Traffic Type
* Malware Indicators
* Anomaly Scores
* Attack Type
* Action Taken
* Severity Level
* Network Segment
* Firewall Logs
* IDS/IPS Alerts
* Log Source

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Exploratory Data Analysis Performed

### Data Exploration

* Dataset Shape Analysis
* Data Type Inspection
* Statistical Summary
* Missing Value Analysis
* Duplicate Record Detection

### Visualizations

* Attack Type Distribution
* Severity Level Distribution
* Protocol Distribution
* Packet Length Histogram
* Anomaly Score Histogram
* Outlier Detection using Boxplots
* Attack Type vs Severity Analysis
* Action Taken Analysis
* Network Segment Analysis
* Log Source Analysis
* Correlation Heatmap
* Pairplot Visualization

## Key Findings

1. The dataset contains 40,000 cybersecurity attack records and 25 attributes.
2. Multiple attack categories are present across the network environment.
3. Severity levels vary significantly between attack types.
4. Anomaly scores help identify potentially malicious activities.
5. Different protocols contribute differently to network traffic patterns.
6. Certain network segments experience a higher concentration of attacks.
7. Security actions such as blocking and logging are frequently used responses.
8. Correlation analysis provides insights into relationships among numerical features.

## Conclusion

The analysis provides valuable insights into cybersecurity threats, network behavior, and attack characteristics. Understanding these patterns can help organizations strengthen threat detection mechanisms, improve monitoring strategies, and enhance overall cybersecurity preparedness.

## Repository Structure

```text
Cybersecurity-Attack-Analysis-EDA/
│
├── Cybersecurity_Attack_EDA.ipynb
├── cybersecurity attack.csv
└── README.md
```

## Author

**Samruddhi Patil**
