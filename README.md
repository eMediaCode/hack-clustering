# Analysing Hacking Attacks

This is the code for a k-means model used to analyse a hacking attack dataset.

## Overview

I built two k-means models to identify whether two hackers or three hackers were involved in an attack. Models were built using the [Apache Spark MLlib](https://spark.apache.org/docs/latest/ml-guide.html) library. The inputs are numeric values. There is no output because this is a clustering project.

The final result based on cluster analysis was that there were only **two** hackers involved with the attacks.

## Dependencies

- spark

Install dependencies using [pip](https://pip.pypa.io/en/stable/).

## Dataset

The (simulated) dataset contains 334 observations (hacking instances) and 7 attributes.

| Column  | Definition |
| ------------- | ------------- |
| Session Connection Time  | How long the session lasted in minutes  |
| Bytes Transferred  | Megabytes transferred during session  |
| Kali Trace Used  | Whether or not the hacker was using Kali Linux  |
| Servers Corrupted  | Number of server corrupted during the attack  |
| Pages Corrupted  | Number of pages illegally accessed  |
| Location  | Location the attack came from  |
| WPM Typing Speed  | Estimated typing speed based on session logs  |

## Usage

Run the notebook on a localhost server using `jupyter notebook`.
