# YouTube Data Analysis and Migration Tool

The YouTube Data Analysis and Migration Tool is a Python application that allows you to collect data from the YouTube Data API, store it in a MySQL database, and perform various data analysis tasks on the collected data. The analysis results are then visualized using a Streamlit web app.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Features

- Collects channel, playlist, video, and comment data from the YouTube Data API.
- Stores the collected data in a MySQL database.
- Performs data analysis on various aspects of the collected data.
- Visualizes analysis results using bar plots.
- Displays analysis results using a Streamlit web app.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x
- MySQL server and credentials
- YouTube Data API credentials

## Installation

1. Clone the repository:
git clone https://github.com/Navo21/YouTube-Data-Analysis.git
cd YouTube-Data-Analysis

2. Install the required Python packages:
pip install -r requirements.txt

## Configuration

1. Create a MySQL database:
- Set up a MySQL server if you don't have one.
- Create a new database (e.g., `youtube_db`) to store the collected data.
- Update the database connection details in the `app.py` file.

2. Obtain YouTube Data API credentials:
- Go to the Google Cloud Console (https://console.developers.google.com/).
- Create a new project and enable the YouTube Data API.
- Create credentials (API Key or OAuth Client ID) and update them in the `app.py` file.

## Usage

1. Run the Streamlit web app:

streamlit run app.py

2. The app will launch in your web browser and display options for data collection, migration, and analysis.

3. Select your desired actions, questions, and parameters to perform data operations and view analysis results.

## Screenshots

Yet to add

## Contributing

Contributions are welcome! If you find any issues or want to add new features, feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details.
