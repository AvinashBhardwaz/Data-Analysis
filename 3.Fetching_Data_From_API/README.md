# Top-Rated Movies Data Collection

## Overview
This project fetches and compiles data on top-rated movies from The Movie Database (TMDb) API using Python. It retrieves movie details across multiple pages and saves the aggregated data into a CSV file for further analysis.

## Technologies Used
- Python
- Pandas
- Requests
- The Movie Database (TMDb) API

## How It Works
1. **API Requests**: The script makes HTTP GET requests to the TMDb API to retrieve top-rated movies.
2. **Data Processing**: The data is processed into a pandas DataFrame, extracting key information such as:
   - Movie ID
   - Title
   - Overview
   - Release Date
   - Popularity
   - Vote Average
   - Vote Count
3. **Data Storage**: The compiled DataFrame is saved to a CSV file named `movies.csv`.

## Getting Started
1. **Clone the Repository**
   ```bash
   git clone https://github.com/AvinashBhardwaz/Data-Analysis.git
   cd Data-Analysis/Working_With_Top_Rated_Movies

