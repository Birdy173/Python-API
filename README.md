# python-api-challenge
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)

## Description
This project takes us through two different Python APIs: OpenWeather API and Geoapify API. It also gets random cities using `citypy`. The script `WeatherPy` finds the weather in these cities and generates the linear regression models to analyze if the weather conditions correlate with latitude and longitude. The `VacationPy` script is all about finding hotels based on your ideal weather conditions. 

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)

## Installation

### Prerequisites

- `matplotlib`: For plotting graphs and data visualizations
- `pandas`: For data manipulation and analysis
- `numpy`: For numerical operations
- `requests`: For making HTTP requests to APIs 
- `time`: For handling time-related tasks
- `scipy.stats`: For linear regression models import linregress
- `api_keys.py`: For handling API keys securely
- `citipy`: For generating random cities

### Steps

1. Clone the repository.
    ```bash
    git clone https://github.com/Birdy173/python-api-challenge.git
    ```
2. Navigate to the project directory.
    ```bash
    cd python-api-challenge
    ```
3. Install dependencies.
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Examples

This can be used to find ideal vacation areas based on weather conditions. 
This can find the closest hotels based on the vacation area.

