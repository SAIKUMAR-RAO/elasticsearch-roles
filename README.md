# Installation and configuration of the elasticsearch cluster on AWS.
# Used the dynamic inventory file considering the virtual machines are on aws.
# Used the ansible vault for encrypting the variable files, pass the --ask-vault-pass during the playbook execution.
# Roles are written for elasticsearch, kibana, metricbeat.
# Requirements: boto, boto3 and botocore 
# ec2 plugin is used for configuring the dynamic inventory
