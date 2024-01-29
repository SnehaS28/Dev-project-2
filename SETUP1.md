# DEVOPS TOOLING WEBSITE SOLUTION
## Setup and technologies used in Project 7
Implementing a tooling website solution that provides access to DevOps tools within the corporate
infrastructure easily accessible.

In this project, I will be implementing a solution that consists of the following components:

1. Infrastructure: AWS
2. Webserver Linux: Red Hat Enterprise Linux 8
3. Database Server: Ubuntu 20.04 + MySQL
4. Storage Server: Red Hat Enterprise Linux 8 + NFS Server
5. Programming Language: PHP
6. Code Repository: GitHub

In the diagram below you can see a common pattern where several stateless Web Servers share a common database and access 
the same files using Network File System (NFS) as a shared file storage. Even though the NFS server might be located on a completely 
separate hardware – for Web Servers it looks like a local file system from where they can serve the same files.


![6000](https://user-images.githubusercontent.com/85270361/210138947-340454da-2ca8-4041-84e7-324d685612a4.PNG)



It is important to know what storage solution is suitable for what use cases, for this – one question needs to be answered: what 
data will be stored, in what format, how this data will be accessed, by whom, from where, how frequently, etc. Based on this, choose the right storage system for your solution.
