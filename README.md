# Twitter Analysis Project using Airflow and Python

## Overview

This project is focused on analyzing Twitter data using the Twitter API and Apache Airflow. It enables you to collect and process tweets, and store the refined data for further analysis.

## Project Goals
1. Twitter Data Collection — Collect tweets from specific Twitter accounts or hashtags.
2. Data Transformation — Process the raw tweet data to extract relevant information.
3. Data Storage — Store the refined data for further analysis.
4. Automation with Airflow — Use Apache Airflow to schedule and automate data collection and processing.
5. Scalability — Ensure the system can handle a large volume of Twitter data.

## Requirements
- Python
- Tweepy library (for Twitter API access)
- Apache Airflow (for data pipeline automation)
- S3 (for data storage, you can use an S3-compatible service)
- Twitter Developer API keys

## Usage
1. Set up Twitter API credentials:
   - `access_key`
   - `access_secret`
   - `consumer_key`
   - `consumer_secret`

2. Create an Apache Airflow DAG that runs the `run_twitter_etl` function to collect and process Twitter data.

3. Configure Airflow to schedule the DAG periodically for automated data collection and processing.

4. Ensure you have access to an S3-compatible storage to store the refined data.

5. Run the Airflow DAG to start collecting and processing Twitter data.

## Credits
This project was developed by Darshil Parmar, and you can find the original code and contributions on his GitHub profile.

