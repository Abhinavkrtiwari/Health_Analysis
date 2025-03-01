# Health Monitoring System

This repository contains the source code, configuration, and reports for a Health Monitoring System that processes health data using Spark and Hadoop.

## Project Overview

The Health Monitoring System is designed to analyze patient health parameters like blood pressure, cholesterol levels, sugar levels, and other vital statistics. The system provides insights through data visualization and machine learning predictions.

## Files in This Repository

### **Code Files**
- **`main.py`** - The main script that processes health data using Spark and Hadoop.
- **`config.py`** - Contains configuration settings for connecting to the data pipeline.
- **`requirements.txt`** - Lists the dependencies required to run the project.

### **Reports and Documents**
- **`Health_Monitoring_Report.docx`** - A detailed report on the findings and analysis of the health data.

### **Data Visualizations**
- **`age_cholesterol_bp_sugar.png`** - A visualization comparing age with cholesterol, blood pressure, and sugar levels.
- **`age_distribution.png`** - Distribution of age across the dataset.
- **`bp_by_gender.png`** - Blood pressure distribution categorized by gender.
- **`bp_vs_cholesterol.png`** - Correlation between blood pressure and cholesterol levels.
- **`correlation_heatmap.png`** - A heatmap showing the correlation between various health parameters.
- **`health_parameter_distributions.png`** - A visualization of various health parameter distributions.

## Setup Instructions

### **1. Install Dependencies**
Run the following command to install all necessary Python packages:
```bash
pip install -r requirements.txt
```

### **2. Run the Main Script**
Execute the main Python script to start the health monitoring analysis:
```bash
python main.py
```

### **3. Configuration**
Modify `config.py` to adjust settings like data source locations, Spark configurations, or storage paths.

## Contributing
Feel free to fork the repository and submit pull requests if you'd like to contribute improvements.

## License
This project is open-source and available for use under the MIT License.
