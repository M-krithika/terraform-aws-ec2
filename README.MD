# terraform aws ec2 module

## inputs:

* ami_id (optional): ami_id is optional, Default value is ami-090252cbe067a9e58 
* security_group_ids (optional): sg_id is optional. Default value is sg-097e211eec2baab9f
* instance_type(optional): default value is t3.micro
* tags(optional): default value is empty.

## outputs:
* public_ip: outputs is the private IP of instance created.
* private_ip: outputs is the private IP of instance created.
instance_id: outputs the instance created.