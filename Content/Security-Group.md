# Security Groups

- You can have multiple ec2 instances in same subnets but they might be requiring different rules. Therefore we have security groups.
- By default all Security group deny all inbound and outbound traffic.
- Security groups perform stateful packet filtering which means any changes which are applied to an incoming rule is automatically applied to a rule which is outgoing.
- If the incoming port of a request is 80, the outgoing response of that request is also 80 (it is opened automatically) by default.
- The security group allows the response to proceed, regardless of inbound security group rules.