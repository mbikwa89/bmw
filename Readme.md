SECTION B


Security:

Various firewall layers have been replaced by security groups and providing the same features of security. All the app servers and web servers were kept as hardened templates and can be used to create more instances if need be.

Cross cutting concerns:

Logs can be redirected to S3 and further old logs can be moved to Glacier. Cloud Watch can be used for monitoring and alerting in case of any incident.

We can utilize amazing features of cloud like multi zone deployment, unlimited and various cheaper mode of storage, auto scaling, RDS, security groups and by using same, we can get a little better version of deployment in cloud compared to on prem deployment.

IAM roles allow you to delegate access with defined permissions to trusted entities without having to share long-term access keys. You can use IAM roles to delegate access to IAM users managed within your account


A security group acts as a virtual firewall for your EC2 instances to control incoming and outgoing traffic.



An IAM role is an IAM entity that defines a set of permissions for making AWS service requests. IAM roles are not associated with a specific user or group. Instead, trusted entities assume roles, such as IAM users, applications, or AWS services such as EC2.



