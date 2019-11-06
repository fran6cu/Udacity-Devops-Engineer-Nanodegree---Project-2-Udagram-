# Udacity Devops Engineer Nanodegree - Project 2 (Udagram)

This is an assignment for the Udacity Devops Engineer Nanodegree program.

The task was to deploy a high availability static website. The website should be hosted on servers within
private subnets. All trafic to the servers should be routed through NAT gateways located in public subnets.
For high availability there should not be any single point of failure and we should leverage auto scaling
as well as security best practices.

To deploy this infrastructure there is a helper script included in the repository. It can be used
like this: `./create.sh <STACKNAME> infra.yml params.json`

To update this infrastructure there is a helper script included in the repository. It can be used
like this: `./update.sh <STACKNAME> infra.yml params.json`

To delete this infrastructure there is a helper script included in the repository. It can be used
like this: `./delete.sh <STACKNAME>`


This is the infrastructure diagram for what this cloudformation script deploys:
![diagram](./architecture.png)
