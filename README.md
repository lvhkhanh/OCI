# OCI
## Glossary
### Availablity Domain vs Available Zone
### Fault Domains vs...
### Compartments vs Resource Group
### VCN(Virual Cloud Network) vs VPC(Virtual Private Cloud)
#### Public subnet
#### Private subnet
### Internet Gateway
### NAT Gateway: outbound only
### Service Gateway: without public internet traffic
### Dynamic routing gateway, v2 vs Transit gateway prevent point to point gateway
#### VPN site to site
#### FastConnect
### Network visualize
### CIDR longer specific will take higher priority in the routing table 192.168.0.0/16 vs 0.0.0.0/0
### Local Peering Gateway in the same region data center
### Security Lists vs Network Access Control Lists
### Network Security Group(network interface card, NSG firewall) vs Security group(EC2)
### Paste cloud init script vs EC2 user data
### Private instance not use public IP
### Add backends instance to load balancer
### Virtual Machine: shared, multi tenant(customer)
### Decicated host: single tenant(customer)
### SSH
```
mkdir .ssh
cd .ssh
ssh-keygen -b 2048 -t rsa -f a-name
# connect to an instance
ssh -i a-name <opc user name>@<public ip>
sudo yum -y install httpd
```
### OKE(Oracle Kubernetes Engine) vs EKS(Elastic Kubernetes Service)
### Oracle Functions vs AWS Lambda
### Object storage Pre-Authenticated request vs S3 Pre-signed request
### Instance configuration
### Block Volume vs Elastic Block Storage: Low cost, balance, high performance, ultra high performance
### Autonômus database: warehouse, transaction(mixed mode), JSON, exadata
### MySQL Database HeatWeave: in memory
