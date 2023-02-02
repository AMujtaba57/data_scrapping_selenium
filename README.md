# Selenium-MySQL-Django Data Scraping
## Introduction
This repository contains a script that scrapes data using Selenium and stores 
it into a MySQL database, as well as a Django web application that allows users 
to interact with the stored data. The script is set up to run as a cron job, allowing 
for automated and periodic scraping.


## Requirements
    * Python 3
    * Selenium
    * MySQL database
    * Django
    * WebDriver for Selenium (e.g. ChromeDriver for Google Chrome)


## Usage
    * Clone the repository to your local machine
    * Install the required packages using pip install -r requirements.txt
    * Set up a MySQL database and update the database credentials in the script and Django settings.
    * Replace the Selenium code with your own custom scraping code.
    * Set up the script to run as a cron job to run automatically at specified intervals.
    * Start the Django development server by running python manage.py runserver.
    * Access the web application through a web browser at http://localhost:8000/.


## Result
[demo video_1](result/scrapping_demo.mp4),
[demo video_2](result/scrapping_demo2.mp4)

## Note
Ensure that the WebDriver is in the PATH, or specify its location in the script.
It is advised to run the script and web application in separate virtual environments 
to avoid conflicts with other packages.

## Author
[Ahmad Mujtaba](http://www.ahmad-mujtaba.com/)
