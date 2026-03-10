# AWS EC2 Monitoring Project Commands
This file contains all the commands used during the AWS EC2 monitoring project.

## 1. Connect to EC2 Instance using SSH
ssh -i linux-for-devops.pem ubuntu@your-public-ip

## 2. Update Linux Packages
sudo apt update

## 3. Install Apache Web Server
sudo apt install apache2 -y

## 4. Start Apache Service
sudo systemctl start apache2

## 5. Check Apache Status
sudo systemctl status apache2

## 6. Enable Apache to Start Automatically
sudo systemctl enable apache2

## 7. Check Running Processes
top

## 8. Check CPU Usage
htop

## 9. Check System Information
uname -a

## 10. Check Disk Usage
df -h

## 11. Check Memory Usage
free -m

## 12. Create High CPU Load (for CloudWatch Alarm Test)
yes > /dev/null

To stop the process:
CTRL + C

## 13. Restart Apache Server
sudo systemctl restart apache2

## 14. Stop Apache Server
sudo systemctl stop apache2
