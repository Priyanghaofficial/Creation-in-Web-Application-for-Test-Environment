 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
  ## AIM
       To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
   Creating a web application for a test environment is essential to provide developers and testers with a dedicated platform to simulate, test, and validate software functionalities. The challenge lies in building an easy-to-use, scalable, and efficient application that supports realistic testing scenarios, automates workflows, and ensures smooth collaboration while minimizing setup and maintenance efforts.

## ALGORITHM
Steps 1:
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
Create a simple HTML page :
```
cd /var/www/html
```
test.php
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>MY FIRST PHP!</title>
</head>
</body>
</html>
```

## OUTPUT
![387726448-00552e94-d63c-4256-a80e-c1375e169862](https://github.com/user-attachments/assets/8833e9e6-26f9-479c-bebe-e2ad054019c4)

![387726577-ae203e89-9e8a-45e7-b63a-cd5d46eba423](https://github.com/user-attachments/assets/6e3689d9-4a5d-44a4-a048-b0415a17c529)
![387726718-2409ed3c-a6bd-4e8f-b4e0-59cb155ea54e](https://github.com/user-attachments/assets/ffb1fd1c-a865-4dac-8936-2ce161604aa4)
![387726822-6284cfea-65fe-4290-9b7a-c2ecb618126a](https://github.com/user-attachments/assets/2a8a4f26-2231-4d1d-83a7-520492c1ffe7)


### REG NUMBER:212223040157
### NAME:PRIYANGHA G
 

## RESULT
Thus the web application for test environment has successfully been created and executed.
 

  


