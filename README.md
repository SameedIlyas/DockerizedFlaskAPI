# Simple Flask API

This repository contains a simple Python Flask API that returns a welcome message when accessed. The API is containerized using Docker, allowing for easy setup and deployment.

## Features

- Flask web framework for handling API requests.
- Docker integration for simple deployment and scalability.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

What you need to install the software:

- Python 3.8 or higher
- Docker

### Installing

A step by step series of examples that tell you how to get a development env running:

1. Clone the repository:
   ~~~
   git clone https://github.com/SameedIlyas/DockerizedFlaskAPI.git
   ~~~
2. Navigate to the Project Directory
3. Build the Docker Container
~~~
docker build -t simple-flask-api
~~~
4. Run the Docker container
~~~
docker run -p 5000:5000 simple-flask-api
~~~

Now, access the API at http://localhost:5000/ to see the welcome message.

