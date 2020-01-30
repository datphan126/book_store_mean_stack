# Book Store - MEAN Stack - AWS EC2
The application in this project is an online Book Store web application where MEAN stack was used for developing the application. The application is intented to be hosted on an AWS EC2 instance.

This project was copied from this [repository](https://github.com/datphan126/CS242_MEAN_fullstack) and was then modified to make it work with my AWS EC2 instance.

# How to run the application
1) Login to your AWS EC2 instance
2) Navigate to the folder named book-store-backend/public
3) Start back-end server: `nohup node app.js &`
4) Navigate to the folder named book-store
5) Start front-end server:
`nohup ng serve --host <ec2_ipv4> --port <port_number> &`
Exit the terminal by using the '**exit**' command (DO NOT CLOSE THE TERMINAL!!!!)

The application can be accessed through this link:

http://<your_ec2_domain_name>:4200
