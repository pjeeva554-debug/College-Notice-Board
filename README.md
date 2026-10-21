# College Notice Board

## Project Description
A simple college notice board website that displays important campus announcements.

## Technologies Used
- HTML
- CSS
- Docker
- Nginx
- GitHub Projects

## Features
- Displays college announcements
- Shows notice publication dates
- Simple and responsive webpage
- Runs using a Docker container

## Docker Commands

Build the image:
docker build -t college-notice-board .

Run the container:
docker run -d --name notice-board -p 8080:80 college-notice-board

Access the website:
http://localhost:8080
