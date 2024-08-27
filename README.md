# GitHub Active Users Estimation

This repository contains code for estimating the total number of active users on GitHub by sampling user IDs in bins and calculating the average number of users per bin.

## Data Crawling: Estimating Total GitHub Users

This part of the project involves estimating the total number of active users on GitHub by sampling user IDs in bins and calculating the average number of users per bin.

## Libraries Used

- `pandas`
- `numpy`
- `requests`
- `json`
- `matplotlib`
- `seaborn`

## Function Definitions

### Calculate Total Users
This function fetches user data in batches starting from a given ID and returns the total number of users in the sample.

### Calculate Average Users
This function calculates the average number of users per bin.

## Bin Size Configurations

The bin size determines how many user IDs are included in each sample. You can configure the bin size according to your needs.

## Creating the DataFrame and Estimating Total Users

This section of the code generates random bins, fetches the user data, and estimates the total number of active GitHub users.

## Visualization

The distribution of user IDs per bin is visualized using a bar plot.

## Saving the Data

The sampled user data is saved to a CSV file.

## Results

The code provides an approximate estimation of the total number of active users on GitHub based on the sampled bins. The visualization shows the distribution of user IDs across the sampled bins.

## Requirements

To run this project, you'll need the following Python libraries:

- `pandas`
- `numpy`
- `requests`
- `json`
- `matplotlib`
- `seaborn`

## How to Run

1. Replace the placeholder `headers` variable with your GitHub API key.
2. Configure the bin size as needed.
3. Run the script to fetch user data, estimate the total user count, and generate visualizations.
