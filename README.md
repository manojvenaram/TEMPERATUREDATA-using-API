
# Temperature Data Collector

This Python script collects temperature data for a list of cities from the OpenWeatherMap API and saves it to a CSV file.

## Requirements
- Python 3.x
- pandas
- requests

## Installation
1. Install the required libraries:
   ```bash
   pip install pandas requests
   ```

## Usage
1. Create a CSV file named `cities_r2.csv` with a column named "name_of_city" containing the list of cities you want to collect data for.
2. Replace `YOUR_API_KEY` in the script with your actual OpenWeatherMap API key.
3. Run the script:
   ```bash
   python your_script_name.py
   ```

## Output
- The script will print the temperature (in Kelvin) and weather description for each city to the console.
- A CSV file named `Temperature23.csv` will be created containing the city, temperature, date, and time of data collection.

## Notes
- The OpenWeatherMap API has usage limits. Ensure you comply with their terms of service.
- You can modify the script to collect additional weather data or customize the output format as needed.

### Example `cities_r2.csv`:
```
name_of_city
London
Paris
New York
Tokyo
```

### Example `Temperature23.csv` output:
```
City,Temperature,Date,Time
London,280.15,2023-11-28,16:32:00
Paris,282.55,2023-11-28,16:32:00
New York,275.15,2023-11-28,16:32:00
Tokyo,285.37,2023-11-28,16:32:00
```

**Use code with caution.**
```

Feel free to adjust the content or formatting as needed! Let me know if you need further assistance.
