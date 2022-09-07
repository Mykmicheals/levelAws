### Deploying static A website to Aws

## Process

- Create an EC2 instance on aws
- Install Linux-Ubuntu Amazon machine image (AMI) or any linux image of your choice
- Create a key-pair Login,for ssh login A .pem file would be downloaded
- Launch the instance
- Connect to the instance via ssh
- Add rules in the security groups
- Allow incoming connection from both ipv4 and ipv6 address on port 80
- Copy static files to /var/www/html
- Launch website via external ip address
