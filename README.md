# NYC Taxi CO2 Emissions Analysis

## Overview
This project analyzes the environmental impact of taxi rides in New York City based on the data provided by the NYC Taxi & Limousine Commission. Utilizing PySpark in Azure Databricks, the project calculates the CO2 emissions for taxi rides and identifies trends in emissions based on trip durations and fare amounts.

## Project Goals
- Calculate CO2 emissions for each taxi ride using the trip distance data.
- Aggregate emissions data to visualize daily trends and compare emissions based on different passenger group sizes.
- Provide insights and recommendations for reducing carbon emissions from taxi rides.

## Tools and Technologies
- **PySpark**: Used for data processing and analysis within Azure Databricks environment.
- **Matplotlib**: For generating scatter plots to visualize emissions data.

## Data
The dataset used includes details about taxi trips such as pickup and dropoff times, locations, distances traveled, and the number of passengers.

## Setup Instructions
1. **Clone the Repository**: 
git clone https://github.com/Dini1999/nyc-taxi-co2-emissions.git
2. **Environment Setup**: 
- Ensure you have access to an Azure Databricks environment.
- Install PySpark if running locally or use Databricks runtime which includes Spark.

3. **Run the Analysis**:
- Import the notebook into your Databricks workspace or run it using your local Spark setup.
- Attach the notebook to a cluster in Databricks and execute all cells.

## Visualizations
This project includes a scatter plot visualization comparing daily CO2 emissions by different passenger counts, highlighting the impact of passenger numbers on emissions.

## Observations and Insights
- Higher emissions are typically observed in rides with fewer passengers.
- Rides with three or more passengers tend to have lower emissions, suggesting efficiencies gained through ride-sharing.

## Contributing
Feel free to fork this repository and submit pull requests with enhancements or fixes.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
