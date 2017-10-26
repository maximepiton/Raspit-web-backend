# Raspit-web-backend

Raspit-web-backend is a service that catches http requests and returns specific weather parameters or images based on existing weather prediction raw data (.nc files).

## Contents

The docker image includes :

* Flask as a server
* NCL for data analysis and image generation

## API endpoints

(Todo)

* /wind-table with location and date as parameters (returns a csv)
* /emagram with location and date as parameters (returns an image)