# Cleaning Data Science at Scale

This is the docker image for the "Cleaning Data Science at Scale" workshop.

## Build

`docker build -t temp .`

## Run

`docker run -d -p 8888:8888 --name notebook temp`

Then browse to http://localhost:8888/notebooks/notebook.ipynb
