1. Installation and configuration of the elasticsearch cluster on AWS.
2. Used the dynamic inventory file considering the virtual machines are on aws.
3. Used the ansible vault for encrypting the variable files, pass the --ask-vault-pass during the playbook execution.
4. Roles are written for elasticsearch, kibana, metricbeat.
5. Requirements: boto, boto3 and botocore 
6. ec2 plugin is used for configuring the dynamic inventory
