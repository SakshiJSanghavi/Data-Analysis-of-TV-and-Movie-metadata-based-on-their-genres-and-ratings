# Weather-Analysis-Project

Welcome to my Weather Analysis Project repository! This project is focused on analyzing a time series dataset containing hourly weather conditions at a specific location. The dataset includes information about temperature, dew point temperature, relative humidity, wind speed, visibility, pressure, and conditions.

## Dataset

The dataset used for this project is available in CSV format and is included in the `data` directory of this repository. The columns in the dataset include:
- Temperature
- Dew Point Temperature
- Relative Humidity
- Wind Speed
- Visibility
- Pressure
- Conditions

## Functions and Insights

In this project, I've implemented various functions to analyze the dataset using the Pandas DataFrame library. Here are some of the insights I've derived from the data:

1. **Unique Wind Speed Values**: Found all the unique 'Wind Speed' values in the data.
2. **Clear Weather Count**: Determined the number of times when the 'Weather is exactly Clear'.
3. **Wind Speed of 4 km/h Count**: Found the number of times when the 'Wind Speed was exactly 4 km/h'.
4. **Null Values**: Identified all the Null Values in the data.
5. **Column Renaming**: Renamed the column name 'Weather' of the DataFrame to 'Weather Condition'.
6. **Mean Visibility**: Calculated the mean 'Visibility'.
7. **Standard Deviation of Pressure**: Calculated the Standard Deviation of 'Pressure' in this data.
8. **Variance of Relative Humidity**: Found the Variance of 'Relative Humidity' in this data.
9. **Instances of Snow**: Identified all instances when 'Snow' was recorded.
10. **Wind Speed and Visibility Criteria**: Found all instances when 'Wind Speed is above 24' and 'Visibility is 25'.
11. **Mean Values by Weather Condition**: Calculated the Mean value of each column against each 'Weather Condition'.
12. **Min and Max Values by Weather Condition**: Found the Minimum and Maximum value of each column against each 'Weather Condition'.
13. **Records with Fog**: Showed all the Records where Weather Condition is 'Fog'.
14. **Clear Weather or Visibility Criteria**: Found all instances when either 'Weather is Clear' or 'Visibility is above 40'.
15. **Complex Criteria**: Identified instances when:
    - A. 'Weather is Clear' and 'Relative Humidity is greater than 50', OR
    - B. 'Visibility is above 40'.

## Files and Directories

- `Weather Data.csv`:The CSV file of the weather dataset.
- `Data Analysis Project-1.ipynb`: Jupyter Notebook containing the analysis code.
- `README.md`: You're currently reading it!

## Getting Started

To explore this project on your local machine, follow these steps:

1. Clone this repository using: `git clone https://github.com/SakshiJSanghavi/Weather-Analysis-Project.git`
2. Open and run the `Data Analysis Project-1.ipynb` notebook to see the data analysis and insights.

## Contributions

Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, feel free to create an issue or submit a pull request.

## Contact

If you have any questions or want to connect, you can reach me at sakshi.sanghavi1016@gmail.com.

Happy exploring and analyzing the weather data!
