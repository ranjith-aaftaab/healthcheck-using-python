#############################################################################################################################

# Website Health Checker

HOLA!!!! Welcome to the Website Health Checker, a simple and efficient web application to monitor the health of websites. With this application, you can easily check the health status of websites and perform security tests. Let's get started!!!

## Prerequisites

Before running the application, please make sure you have the following requirements installed on your system:

- **Python 3**: You can download and install Python 3 from the official Python website: [python.org](https://www.python.org/).

## Installation

To install the necessary dependencies, please follow these steps:

1. Clone this repository or download the source code to your local machine.

2. Open a terminal or command prompt and navigate to the project directory.

3. Install the required packages by running the following command:(COPY WITHOUT COLUMNS PLAESEEEEE)
   
   """"pip install -r requirements"""""""
   

   This command will automatically install Flask, requests, and other dependencies needed for the application.

## Usage

Now, let's run the Website Health Checker and start monitoring website health:

1. In the terminal or command prompt, navigate to the project directory if you haven't already.

2. Run the following command to start the Flask application:(PLEASE COPY WITHOUT COLUMNS)
   
   """"python backend.py"""""
   

   You should see some startup messages indicating that the server is running.

3. Open your web browser and visit `http://localhost:5000`. This is the homepage of the Website Health Checker.

4. On the homepage, you will find an input field labeled "Enter Website URL". Simply enter the URL of the website you want to check and click the "Check Health" button.

5. The application will initiate the health check and perform a security test on the provided website. You will be redirected to a result page displaying the website URL, health status, Redis output, and security test result.

6. To check the health of another website, simply click the "Back to Home" link and repeat the process.

That's it! You can now efficiently monitor website health with the Website Health Checker.

## IMP Notes

- The application stores the website health data in an SQLite database named `website_health.db`. You don't need to create the database manually as it will be created automatically when you run the application.

- The application utilizes Redis as an in-memory data store to cache the results. Ensure that Redis is installed and running on your system. By default, the application connects to Redis running on `localhost` with the default port `6379`.

- For demonstration purposes, the application inserts random data into the `website_health` table in the database at startup. If needed, you can modify or remove this code in the `insert_random_data()` function.



                                            











































______kaushik________#####################################################################################################################