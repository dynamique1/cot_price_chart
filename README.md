# COT Data and EUR Exchange Rate Analysis

This project fetches and analyzes Commitments of Traders (COT) data and EUR exchange rate data. The project uses Python for data fetching, processing, and visualization.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/dynamique1/ecb_interestrate_history.git
    cd ecb_interestrate_history
    ```

2. **Create a virtual environment (optional but recommended):**

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Fetch COT data:**

    Run the script to scrape and save COT data:

    ```bash
    python cot_data_scraper.py  # Replace with the actual script name if different
    ```

    This will download the COT data and save it to a local CSV file named `cot_data.csv`.

2. **Analyze EUR exchange rate and COT data:**

    Open the Jupyter notebooks to analyze and visualize the data:

    - For EUR exchange rate analysis:
    
        ```bash
        jupyter notebook ecb_interest_analysis.ipynb
        ```

    - For COT price analysis:
    
        ```bash
        jupyter notebook cot_price_analysis.ipynb
        ```

## Features

- Fetch Commitments of Traders (COT) data.
- Analyze EUR exchange rate data from a CSV file.
- Process and clean the data for analysis.
- Generate visualizations to display trends and patterns in the data.
- Cache data locally to avoid frequent API calls.

## Project Structure

- `cot_data_scraper.py`: Script to fetch COT data. *(Replace with the actual script name if different)*
- `ecb_interest_analysis.ipynb`: Jupyter notebook to analyze and visualize the EUR exchange rate data.
- `cot_price_analysis.ipynb`: Jupyter notebook to analyze and visualize the COT data.
- `cot_data.csv`: CSV file containing the COT data.
- `interest_rate_history.csv`: CSV file containing the EUR exchange rate data.
- `requirements.txt`: List of required dependencies.
- `README.md`: Project documentation.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-branch`
5. Open a pull request.

Please ensure your code follows the project's coding conventions and includes appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
