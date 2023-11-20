# Filtering Airbnb Reviews: London Dataset

This repository contains a Python script for filtering and cleaning Airbnb reviews data for the city of London. The script utilizes the pandas library to read a CSV file containing Airbnb reviews, applies date filtering to retain entries on or after September 1, 2022, and exports the processed data to a new CSV file.

## Dataset Information

The original dataset includes reviews with the following columns:
- `listing_id`: ID of the Airbnb listing
- `id`: Review ID
- `date`: Review date (converted to datetime format)
- `reviewer_id`: ID of the reviewer
- `reviewer_name`: Name of the reviewer
- `comments`: Review comments

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your_username/Filtering-Airbnb-Reviews-London-Dataset.git
   cd Filtering-Airbnb-Reviews-London-Dataset
