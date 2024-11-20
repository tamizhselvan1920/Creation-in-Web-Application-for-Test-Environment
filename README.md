

  

 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT

 NAME: THAMIZH SELVAN R

 REG NO: 212222230158
 
## AIM  
To Creation in Web Application for Test Environment.

## PROBLEM STATEMENT
Explain about the Experiment.

## ALGORITHM
Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.

Steps 2:
Connect to the instance using SSH and install a web server like Apache

Steps 3:
Create a simple HTML file in the server's default directory with basic content for testing.

Steps 4:
Access the instance's public IP in a browser to verify the HTML page is displayed.
## COMMANDS
To install httpd:
```
yum install httpd -y
```
To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```

 ## OUTPUT
 
Terminal:

![image](https://github.com/user-attachments/assets/99912383-5d3b-40f5-b2bc-a799c6274cb3)
Website:

![image](https://github.com/user-attachments/assets/1fc1cf5c-63b9-47c3-bfc9-abbcfd12fec3)


## RESULT
 Thus the web application for test environment has successfully been created and executed.
