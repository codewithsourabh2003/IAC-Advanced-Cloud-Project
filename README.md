# IAC-Advanced-Cloud-Project
# IAC Project using CloudFormation (high availability web app)
 > This is the IAC project for the [Cloud DevOps Engineer Nano-degree on Udacity](https://www.udacity.com/course/cloud-dev-ops-nanodegree--nd9991).
 ---
 ### Problem Summary
 > Create a launch configuration to deploy 4 servers (2 in each private subnet). You need 2 vCPUs with at least 4GB of RAM. The OS is required to be Ubuntu 18. So choose the AMI that best fits the specs and allocate at least 10 GB of disk space.
 
 > The application communicates on the default HTTP port, and as for the application archive it is downloaded from an S3 bucket. So use the required resources and traffic control.
 
 > You can provide SSH key for developer access to troubleshoot while creating the script.
 ---
 ### My Cloud Architecture Design
 ![Cloud Architecture Diagram](Cloud-Architecture-Diagram.png)
 ---
 ### IAC Files
 * Network Infrastructure Stack
   * Template: network.yml
   * Parameters: network-parameters.json
 
 * Servers Stack
   * Template: servers.yml
   * Parameters: servers-parameters.json
 
 ---
 ### Helper Bash Scripts
 > I have also provided helper bash scripts for creating, updating and deleting the stacks mentioned above.
 ---
