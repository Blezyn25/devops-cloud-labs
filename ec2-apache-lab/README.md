# EC2, Apache, User Data and IAM User profile

Launched an Amazon Linux EC2 instance and connected via SSH from Git Bash.

Installed, started and enabled Apache, served a custom 'index.html' page from '/var/www/html'.

Explored how User Data automates server setup on first boot.

Created an IAM Instance profile so the instance can use temporary role credentials instead of hard coded access keys.

## Issues I debugged

- Restored port 22 in the security group when SSH timed out.
- Tested on 'HTTP://' instead of 'HTTPS://' for port 80 traffic.
