
User Data

```bash

#!/bin/bash

yum update -y
yum install -y httpd
yum install -y wget
cd /var/www/html
wget https://raw.githubusercontent.com/awsdevopsteam/itfpath/main/index.html
wget https://raw.githubusercontent.com/awsdevopsteam/itfpath/main/devops.jpg
systemctl start httpd
systemctl enable httpd

```
