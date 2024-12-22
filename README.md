**Here's a step-by-step guide to running server on AWS:**





## Step 1: Launch an EC2 



1. Log in to the AWS Management Console.

2. Navigate to the EC2 dashboard.

3. Click "Launch Instance" and selected the desired Amazon Machine Image (AMI) that is Ubuntu.

4. Choose the instance type and configure the instance details.

5. Add storage and tags as needed.

6. Configure the security group to allow inbound traffic on the necessary ports (e.g., port 80 for HTTP).

7. Review and launch the instance.





## Step 2: Connect to Your EC2 Instance



1. Go to the EC2 dashboard and select the instance.

2. Click "Actions" and then "Connect to instance".

3. Follow the instructions to connect to your instance using SSH.





## Step 3: Install and Configure Apache2



1. Connect to your EC2 instance using SSH Client.

2. Install Apache using the package manager (e.g., `sudo apt-get install apache2` on Ubuntu-based systems).

3. Configure Apache to listen on the desired port (e.g., port 80).





## Step 4: Deploy Project



1. Copy HTML files to the EC2 instance.

2. Move your HTML file to the Apache2 document root directory:





## Step 5: Configure Security Groups



1. Go to the EC2 dashboard and select the instance.

2. Click "Actions" and then "Networking" > "Change security groups".

3. Add a new rule to the security group to allow inbound traffic on the necessary ports (e.g., port 80).





## Step 6: Test Your Website



1. Go to a web browser and navigate to your website using the public IP address of your instance.

2. Verify that your HTML page is displayed correctly.


<br>

## Public IP Address
[Public IP Address:] (http://54.77.22.164)

