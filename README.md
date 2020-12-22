# Data Modeling with Apache Cassandra
This program demonstrates the use of NoSQL data modeling concepts using Apache Cassandra.

## Installation
Download the files for the project by cloning this repo:

    git clone https://github.com/berliner2020/sparkify-no-sql.git


Inside the newly created directory 'sparkify-no-sql', create a virtual environment:

    python3 -m pip install --user virtualenv
    python3 -m venv env
    source env/bin/activate

You can read more about setting up virtual environments here:
https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment

Install the dependencies and libraries

    pip install -r requirements.txt

## Setting up Apache Cassandra in Docker
Once Docker is installed on your local machine and the Docker daemon is running:

    docker pull cassandra
    docker run --name sparkify -p 127.0.0.1:9042:9042 -d cassandra

This will download the latest Cassandra image to your machine and allow you to run a container with it running in it.

## Run the Program
Open up the terminal in your IDE and run the notebook by entering:

    jupyter notebook Project_1B_ Project_Template.ipynb
