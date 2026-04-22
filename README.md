# Data-Masking-System
## Overview

This project is a Python-based data masking web application designed to
protect sensitive information in datasets. It enables users to upload
CSV files, apply masking techniques to personally identifiable
information (PII), and download anonymized data while preserving the
original structure for analysis and testing.

## Features

-   Upload and process CSV datasets
-   Mask sensitive fields such as names, emails, and phone numbers
-   Generate realistic fake data using Faker
-   Maintain consistent masking for repeated values
-   Preserve dataset structure and usability
-   Simple web interface built with Flask

## Technologies Used

-   Python
-   Flask
-   Pandas
-   Faker
-   HTML/CSS

## How It Works

The system reads the uploaded CSV file, applies masking rules to
sensitive fields, and replaces original values with realistic synthetic
data. It ensures consistency across repeated entries and outputs a
masked CSV file for download.

## Installation

1.  Clone the repository
2.  Install required dependencies: pip install flask pandas faker
3.  Run the application: python app.py

## Usage

-   Open the web interface in your browser
-   Upload a CSV file
-   Click on "Upload and Mask Data"
-   Download the masked file

## Project Structure

-   app.py -- Main Flask application
-   templates/ -- HTML interface files
-   input/output files -- CSV datasets

## Contribution

Contributions are welcome. Please feel free to submit a pull request.

## License

This project is for educational and professional portfolio purposes.

If you like this project, please give it a star.
