# Udagram-Neeru
This project contains file to deploy Udacity Udagram project.

# Steps to Run:
1) Create network elements by running the udagram-infra.yml
.\aws_create_stack.bat udagram-infra .\udagram-infra.yml .\udagram-infra-params.json

2) Create servers and associated elemets by running udagram-servers.yml
.\aws_create_stack.bat udagram-server-stack .\udagram-servers.yml .\udagram-server-params.json

# Application URL will be avaialble in the "OUTPUT" section of Cloudformation stack of "udagram-server-stack"
