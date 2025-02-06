Case Study - Senior Cloud Engineer
To streamline the process of managing automation recipes, our company requires a robust cloud infrastructure that enables quick and efficient recipe storage, consolidation, and distribution to our customers. The goal is to design a cloud infrastructure which facilitates creation of zip-archives of recipes and their exchange in a streamlined and secure way.

What is a recipe?
A recipe is a set of instructions that a robotic arm follows to complete tasks. These instructions can cover a variety of actions, from recognizing screws to unscrewing them, and picking up various components of a battery.

Tasks
A) You are tasked with designing a cloud infrastructure that meets the following requirements:
1. Storage:
- The storage system must efficiently handle both large binary files (1+ GB) and small configuration files at scale.
- The storage solution should include a version control mechanism, like what is found in Git environments, to track and manage changes to these files.
2. Consolidation:
- Both large and small files should be consolidated into a single archive (e.g., a zip file) for easier distribution.
- This consolidated archive must also be securely stored in the cloud. 3. Distribution:
- Enable secure, and efficient distribution of the consolidated recipe files to customers.
- Ensure the distribution process is optimized for global reach, providing fast and
reliable delivery regardless of location.
- Implement an access control system to govern who can access the recipe.
 4. Network:
- Establish a secure connection between the on-premises network and the cloud
infrastructure via VPN.
5. Security:
- Security considerations must be carefully addressed, with particular attention to data
encryption during storage and transmission.

High-level architecture diagram can be found in file: Senior Cloud Engineer Case Study.drawio

B) Implement Infrastructure as Code (IaC) to deploy a free-tier file storage service and a serverless function. The serverless function should be configured to automate the transfer of files from one storage service to another.
Technology used: AWS CloudFormation
File: AWSTemplateFormatVersion/ 2010-09-09.yml

C) Additionally, provide brief insights into the benefits, potential pitfalls, and important considerations surrounding the following topics:
- IaC
- IoT and Edge computing
- Cost calculations and optimisations
Answer provided in powerpoint slide
