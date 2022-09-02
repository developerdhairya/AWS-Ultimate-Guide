# Amazon-Elastic-Load-Balancing

- Elastic Load Balancing (ELB) is the AWS service that automatically distributes incoming application traffic across multiple resources, such as Amazon EC2 instances.
- ELB is a regional construct because it runs at a regional level rather than individual ec2 instances making the service highly available.
- It coordinates with Amazon EC2 Auto Scaling service to scale up and scale out instances based on traffic.
- This diagram depicts that there is ony one point of contact for ordering tier and when new instances are added to production tier it only need to inform to ELB not to all the Ordering tier devices not to all ordering tier devices.

![ELB](../Images/ELB.png)