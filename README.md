

---

# F1 2023 Season Analysis

## Overview

This repository contains a detailed analysis of the **Formula 1 2023 season**, focusing on lap times, tire strategies, and stint lengths of drivers across multiple races. The project uses data from the `FastF1` Python package to extract and visualize performance metrics, primarily targeting the top 3 drivers from each race. The goal is to provide a clear view of driver performance across different races and tire compounds.

## Features

- **Lap Time Analysis**: Visualizes lap times for the top 3 drivers in each race of the 2023 F1 season.
- **Tire Stint Visualization**: Shows the tire compounds and stint lengths for the top 3 drivers.
- **Dynamic Driver Selection**: Automatically selects the top 3 drivers for each race based on finishing positions.
- **Race-by-Race Comparison**: Loops through multiple races and presents detailed graphs for each.

## Data Sources

The data for this analysis is sourced from the `FastF1` Python library, which provides comprehensive telemetry, lap, and race data for Formula 1 seasons. The dataset includes:
- Driver lap times
- Tire compounds used in each stint
- Driver positions

## Requirements

### Python Packages

Before running the project, ensure you have the following packages installed:
- `fastf1`
- `matplotlib`
- `pandas`

You can install them using the following command:

```bash
pip install fastf1 matplotlib pandas
```

### Jupyter Notebook

If you prefer to run the project using Jupyter Notebook, you can install it with:

```bash
pip install notebook
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/f1-2023-season-analysis.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Open and run the Jupyter notebook:

```bash
jupyter notebook
```

4. The script will automatically load data for each race in the 2023 season and visualize lap times and stints for the top 3 drivers.

## Code Structure

- **`f1_analysis.ipynb`**: The Jupyter notebook that performs the data extraction, analysis, and visualization.
- **Lap Time Plot**: A graph plotting the lap times for the top 3 drivers of each race.
- **Stint Length Bar Plot**: A horizontal bar graph showing the stint lengths and tire compounds used by each driver.

## Example Output

The notebook generates visualizations such as:
- A **Lap Time Plot** comparing the lap times of the top 3 drivers across a race.
- A **Tire Stint Visualization**, showing which tire compounds were used during the race and the length of each stint.

![Lap Time Example](example-laptimes.png)
*Lap Times for the Saudi Arabia Grand Prix 2023*

## How It Works

1. **Data Loading**: The project uses the `FastF1` library to fetch race data from the 2023 Formula 1 season.
2. **Driver Selection**: For each race, the top 3 drivers are selected based on their final position.
3. **Lap Time Visualization**: The script plots the lap times for the top 3 drivers of the race.
4. **Tire Strategy**: It also plots the stint lengths and compounds used by these drivers.

## Future Improvements

- Include a comparison between the full grid of drivers for a more in-depth analysis.
- Add interactive plots using libraries like Plotly for dynamic data exploration.
- Expand the analysis to include telemetry data such as speed and acceleration.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue with any suggestions for improvement.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
