# Hotel Booking Analysis

## Overview
This project conducts an analysis of a hotel booking dataset obtained from Kaggle. The dataset used can be found [here](https://www.kaggle.com/datasets/mojtaba142/hotel-booking). It covers various aspects of data manipulation, cleaning, exploration, and visualization to derive insights about roller coasters.

## Environment Setup

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/SartazAnsari/hotel-booking-analysis.git
   cd hotel-booking-analysis
   ```

2. ### Conda Setup
    1. Create a new Conda environment:
        ```
        conda create --name hotel-booking-analysis-env python=3.12
        ```
    2. Activate the environment:
        ```
        conda activate hotel-booking-analysis
        ```
    3. Install the required packages:
        ```
        conda install -c conda-forge ipykernel
        conda install -c conda-forge kaggle
        # if not installed
        conda install pandas matplotlib seaborn 
        ```
3. ### Python Setup (Alternative)
    1. If you prefer Python’s built-in virtual environment
        ```
        python -m venv hotel-booking-analysis-env
        ```
    2. Activate the environment:
        * Windows:
            ```
            hotel-booking-analysis-env\Scripts\activate
            ```
        * Unix or MacOS:
            ```
            source hotel-booking-analysis-env/bin/activate

            ```
    3. Install the required packages:
        ```
        pip install ipykernel
        pip install kaggle
        pip install pandas matplotlib seaborn
        ```

## Setting up the Kaggle API
1. Sign in to **Kaggle** and navigate to the **Account** tab of your user profile.
2. Scroll down to the **API** section and click on **Create New API Token**. 
3. This will download a file named ```kaggle.json``` containing your API credentials.
4. Place the ```kaggle.json``` file in the ```~/.kaggle/``` directory. If the directory does not exist, create it.
5. You're all set up! You can now use the Kaggle API to download datasets directly to your project.

## Analysis
1. **Hotel Booking Status:** Visualize the proportion of canceled and non-canceled bookings using pie charts.
2. **Customer Types:** Plot the proportion of different customer types using a horizontal bar chart.
3. **Deposit Types:** Visualize the proportion of different deposit types using a pie chart.
4. **Distribution Channels:** Plot the proportion of bookings made through different distribution channels using a bar chart.
5. **Hotel Comparison:** Compare booking status between City Hotel and Resort Hotel using a count plot.
6. **Cancellation Trends Over Time:** Analyze cancellation trends over time using a time series plot.
7. **Total Cancellations of Hotels:** Plot the total cancellations of City Hotel and Resort Hotel over time.
8. **Average ADR of Hotels:** Visualize the average ADR (Average Daily Rate) of City Hotel and Resort Hotel over time.
9. **Average Lead Time:** Analyze the average lead time for bookings in City Hotel and Resort Hotel over time.

## Usage
1. Ensure the dataset is available in the project directory.
2. Import the necessary libraries and functions.
3. Run the provided Python script to perform the analysis and generate visualizations.