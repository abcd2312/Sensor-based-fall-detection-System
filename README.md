# Sensor-based-fall-detection-System
Accelerometer Data Processing and Feature Extraction
This Python project provides a comprehensive solution for processing and analyzing accelerometer data. It automates the renaming of CSV file columns, consolidates the data into a single ZIP archive, and extracts a wide range of features from the raw sensor measurements.
Features
CSV File Renaming: The script renames the first column of all CSV files in a specified directory to 'timestamp', ensuring consistent data structure.
CSV File Zipping: All the renamed CSV files are zipped into a single archive named 'renamed_csv_files.zip' for convenient storage and distribution.
Accelerometer Data Processing: The script processes the accelerometer data to extract the following features:
Peak acceleration in each axis (x, y, z)
Impact magnitude
Jerk signals (maximum values)
Energy measures
Skewness and kurtosis
Zero-crossing rate
Tilt angle
Windowed statistics (mean and standard deviation)
Minimum and average values
Time-related metrics
These features are stored in a single DataFrame, which can be used for further analysis or machine learning tasks.
