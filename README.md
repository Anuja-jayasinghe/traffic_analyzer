# Traffic Analyzer

**Traffic Analyzer** is a Python-based application designed to process and visualize traffic survey data from CSV files. It provides detailed analysis and graphical histograms to help users understand vehicle flow patterns and key traffic metrics.

## Features

### Traffic Data Analysis:
Processes traffic survey data to extract insights like:
- Total vehicles
- Truck counts
- Electric vehicle usage
- Two-wheeled vehicles (bicycles, motorcycles, scooters)
- Peak traffic hours
- Speeding violations
- Weather impact on traffic

### Histogram Visualization:
Generates dynamic and resizable histograms to visually represent vehicle frequency per hour at junctions:
- **Elm Avenue/Rabbit Road**
- **Hanley Highway/Westway**

### CSV File Management:
- Validates user input for survey date and loads corresponding CSV files.
- Saves results in a user-friendly text format (`results.txt`).

### Interactive User Experience:
- Offers options to analyze additional files.
- Handles invalid input gracefully.
- Provides a responsive graphical interface using `tkinter`.

## Getting Started

### Prerequisites
- **Python 3.1+**
- Required libraries:
  - `tkinter` (for GUI functionality)
  - `csv` (for handling data processing)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Anuja-jayasinghe/traffic_analyzer.git
