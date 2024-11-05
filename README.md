# AWS-AZURE-CLOUD
AWS AZURE CLOUD 

sudo apt update

wget https://s3.amazonaws.com/amazoncloudwatch-agent/ubuntu/amd64/latest/amazon-cloudwatch-agent.deb
sudo dpkg -i -E ./amazon-cloudwatch-agent.deb
sudo /opt/aws/amazon-cloudwatch-agent/bin/amazon-cloudwatch-agent-config-wizard


sudo systemctl start amazon-cloudwatch-agent
sudo systemctl enable amazon-cloudwatch-agent

tail -f /opt/aws/amazon-cloudwatch-agent/logs/amazon-cloudwatch-agent.log
