# 2048 Game Project

This project is a deployment of the popular 2048 game on AWS Elastic Beanstalk using Docker. The game code has been sourced from the [2048 GitHub repository](https://github.com/gabrielecirulli/2048).

## Deployment Details

### AWS Elastic Beanstalk

- This project is hosted on AWS Elastic Beanstalk, making it easily accessible and scalable.
- The free tier-eligible services provided by AWS Beanstalk are utilized, ensuring cost-effectiveness.

### Docker Image

- The application is packaged inside a Docker container for portability and consistency.
- The Dockerfile used for the container includes all the necessary instructions for setting up the environment and deploying the game.

### NGINX Server

- NGINX is used as the web server to serve the game to users.
- It is configured to run as a daemon in the Docker container.

## Deployment Steps

To deploy this project on your own AWS Elastic Beanstalk environment, you can follow this link https://medium.com/@pawararjun0802/deploying-the-2048-game-on-aws-beanstalk-using-docker-2dae72498192

This README.md file provides an overview of your project, deployment details, and instructions for others to deploy the game on their own AWS Elastic Beanstalk environment.


