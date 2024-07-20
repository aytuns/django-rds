# Connecting Django App to AWS RDS MySQL

This repo connects a simple Django app to an AWS RDS MySQL database.

## Prerequisites

Before you begin, make sure you have the following:

- An AWS account with RDS service enabled, and configured for MYSQL.
- A Django app set up and running locally.

## Steps

1. Create an RDS MySQL instance in your AWS account.
2. Note down the endpoint, username, password, and database name of your RDS instance.
3. Install the `mysqlclient` package in your Django app's virtual environment (run the `requirements.txt` file from this repo in your virtual environment).
4. Update your Django app's `settings.py` file with the RDS MySQL database configuration.
5. Run migrations to create the necessary tables in the RDS MySQL database.
6. Test the connection by running your Django app locally.


