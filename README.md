# Hotel Booking Analysis

## Overview
This project conducts an analysis of a hotel booking dataset obtained from Kaggle. The dataset used can be found [here](https://www.kaggle.com/datasets/mojtaba142/hotel-booking). It covers various aspects of data manipulation, cleaning, exploration, and visualization to derive insights.

## Viewing the Notebook
For better readability due to custom client display functionality, use [nbviewer](https://nbviewer.org). This provides an improved display as GitHub's notebook viewer does not execute the code.
* [HotelBookingAnalysis.ipynb](https://nbviewer.org/github/SartazAnsari/hotel-booking-analysis/blob/main/HotelBookingAnalysis.ipynb)

## Prerequisites
* **Python 3.x:** Download and install from [python.org](https://www.python.org/).

## Setup

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/SartazAnsari/hotel-booking-analysis.git
   cd hotel-booking-analysis
   ```

2. **[ CHOOSE ANYONE ] Environment setup**
    * Using **Python**
        1. Create virtual environment: 
            ```bash
            python -m venv hotel-booking-analysis-env
            ```
        2. Activate the environment:
            * Windows:
                ```bash
                hotel-booking-analysis-env\Scripts\activate
                ```
            * Unix or MacOS:
                ```bash
                source hotel-booking-analysis-env/bin/activate

                ```
        3. Install the required packages:
            ```bash
            pip install ipykernel
            pip install kaggle
            pip install pandas matplotlib seaborn
            ```
    * Using **Conda**
        1. Install **Miniconda/Anaconda**: Download and install from [conda.io](https://conda.io).
        2. Create a new Conda environment:
            ```bash
            conda create --name hotel-booking-analysis-env python=3.12
            ```
        3. Activate the environment:
            ```bash
            conda activate hotel-booking-analysis
            ```
        4. Install the required packages:
            ```bash
            conda install -c conda-forge ipykernel
            conda install -c conda-forge kaggle
            conda install pandas matplotlib seaborn 
            ```

3. **[ IF NOT SET BEFORE ] Setting up the Kaggle API**
    * Sign in to **Kaggle** and navigate to the **Account** tab of your user profile.
    * Scroll down to the **API** section and click on **Create New API Token**. 
    * This will download a file named ```kaggle.json``` containing your API credentials.
    * Place the ```kaggle.json``` file in the ```~/.kaggle/``` directory. If the directory does not exist, create it.
    * You're all set up! You can now use the Kaggle API to download datasets directly to your project.

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