DOS Attack Simulation and Detection Project
Description

This project focuses on simulating and detecting DOS attacks using Python. Detected attacks are logged into a local CSV database. Based on this data, analyses are performed in a Jupyter Notebook to answer questions such as the location of suspicious IP addresses and the most common types of attacks.
Features

    DOS Attack Simulation: Simulate DOS attacks using randomly generated IP addresses.
    Attack Detection: Monitor and detect attacks using the SniffnDetect module.
    Data Logging: Detected attacks are recorded in a CSV file.
    Data Analysis: Suspicious IP addresses are geolocated using the ip-api.com service, and the most common types of attacks are visualized in the Jupyter Notebook.

Project Structure

The project contains the following files:

    attacks.py: Script to simulate DOS attacks.
    app.py: Main script for attack detection.
    ddos_attack_analysis.csv: Local CSV file where detected attacks are logged.
    Jupyter.ipynb: Jupyter Notebook used to answer project questions with code snippets and visualizations.

Questions Addressed in the Jupyter Notebook

    Where are the suspicious IP addresses located?
        Using the ip-api.com service to map the IP addresses.
    What is the most common type of attack?
        Analysis of the most frequent attacks based on the logged data.

Prerequisites

    Python 3.x
    Required libraries:
        Scapy
        Requests
        Pandas
        Matplotlib
        Other libraries listed in requirements.txt

Installation

    Clone this repository:

    bash

git clone https://github.com/Khalil68/Project-DOS.git

Install the dependencies:

bash

    pip install -r requirements.txt

Usage

    Run the DOS attack simulation:

    bash

python attacks.py

Run the attack detection:

bash

    python app.py

    Analyze the data and view results: Open Jupyter.ipynb in Jupyter Notebook and execute the cells.

Author

DAOUDI Khalil
