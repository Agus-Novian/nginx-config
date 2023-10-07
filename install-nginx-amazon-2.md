# Check If amazon-linux-extras is installed
which amazon-linux-extras

# Just in case it’s not installed, you can install it using the below command.
sudo yum install -y amazon-linux-extras

# Look for the Nginx package in the amazon-linux-extras repo
amazon-linux-extras list | grep nginx

#
sudo amazon-linux-extras install nginx1

sudo systemctl enable nginx

sudo systemctl start nginx
