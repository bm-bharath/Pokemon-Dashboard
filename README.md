# Pokémon Dashboard

## Overview

The Pokémon Dashboard is an interactive web application built with Panel and HoloViews. It allows users to explore and visualize various statistics of Pokémon. Users can filter Pokémon data by generation and base stats, and view the results through interactive plots and tables.

## Features

- **Interactive Scatter Plot**: Visualize the relationship between Attack and Defense stats.
- **Type Distribution Bar Plot**: See the distribution of different Pokémon types.
- **Speed Distribution Histogram**: Analyze the speed distribution of Pokémon.
- **Interactive Table**: Browse and sort detailed Pokémon data.

## Getting Started

### Prerequisites

Ensure you have Python 3.7 or higher installed. Install the required Python packages using the provided `requirements.txt` file.

### Installation

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/pokemon-dashboard.git
    cd pokemon-dashboard
    ```

2. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Prepare Data**:
   - Ensure your CSV file `pokemon_data.csv` is in the project directory.
   - The CSV file should include the following columns: `total`, `attack`, `defense`, `speed`, `generation`, `type1`.

4. **Add Image**:
   - Place an image named `pokemon_image.png` in the project directory for the sidebar.

### Running the Dashboard

1. **Run the Dashboard**:
    ```sh
    python pokemon_dashboard.py
    ```

2. **View the Dashboard**:
   - Open the link provided in the terminal to interact with the dashboard in your web browser.

## Usage

1. **Filters**:
   - **Generation**: Select the Pokémon generation you want to explore using the radio button group.
   - **Base Stat Filter**: Adjust the slider to filter Pokémon based on their total base stats.

2. **Visualizations**:
   - **Scatter Plot**: View Attack vs. Defense stats for the filtered Pokémon.
   - **Bar Plot**: Check the count of each Pokémon type for the selected filters.
   - **Histogram**: Examine the distribution of Speed stats.
   - **Interactive Table**: Explore detailed information about the filtered Pokémon.

### Dashboard Layout

- **Sidebar**:
  - Title, description, image, and filter widgets.
- **Main Area**:
  - Scatter plot, bar plot, histogram, and interactive table displayed in a responsive layout.

### Example

![Pokémon Dashboard](pokemon_image.png)

## Contributing

We welcome contributions! Feel free to open issues or submit pull requests with improvements and suggestions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or comments, please contact bharathbm83@gmail.com.


