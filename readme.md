# Difference between Security group and Network control access list (NACL)
Comparison: VPC Security Group vs NACL in AWS.

Security Group

is the firewall of EC2 Instances

Network ACL

is the firewall of the VPC Subnets
## Key Differences: Security group vs NACL
Scope: Subnet or Instance (where to apply)
Security Groups operate at the Instance (Network Interface) level. Security Group has to be assigned explicitly to the instance.

Network ACLs at the subnet level. Applies automatically to all instances deployed in the associated subnet.