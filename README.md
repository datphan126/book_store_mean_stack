# Book Store - MEAN Stack - AWS EC2
The application in this project is an online Book Store web application where MEAN stack was used for developing the application. The application is intented to be hosted on an AWS EC2 instance.

This project was copied from this [repository](https://github.com/datphan126/CS242_MEAN_fullstack) and was then modified to make it work with my AWS EC2 instance.

# How to run the application
1) Login to your AWS EC2 instance
2) Setup Node on your machine
3) Navigate to the folder book-store-backend
4) Run the command `npm i` to install all required dependencies for the back-end server
5) Navigate to book-store-backend/src
6) Run `npm run tsc` to build your bacnkend's code
7) Navigate to book-store-backend/public
8) Start the backend server:
**`nohup node app.js &`**
9) Navigate to the folder book-store
10) Run the command `npm i` to install all required dependencies for the front-end server
11) Start the front-end server:
**`nohup ng serve --host <ec2_ipv4> --port <port_number> &`**
12) Exit the terminal by using the '**exit**' command (DO NOT CLOSE THE TERMINAL!!!!)
13) The application can be accessed through this link:
**http://<your_ec2_domain_name>:4200**
