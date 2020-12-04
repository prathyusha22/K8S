# Flow Diagram


![alt text](https://mediaimag.s3-us-west-2.amazonaws.com/arch.png)

# Technologies used to deploy mediawiki application
   
    •  Terraform 
    •  Kubernetes
    •  AWS
    •  Jenkins 

# Objective

•	To automate the deployment of MediaWiki.

# Process/Steps needs to follow

•	Create a Jenkins pipeline job.

•	Choose SCM as GIT.

•	Provide the github URL(https://github.com/KrishnaMouli/assignment-thoughtworks.git) as Repository URL.

•	Script path as Jenkinsfile.

•	Run the Job.

•	Once job deployed successfully endpoint url and db name will get printed in the job console output as shown below.
 
![alt text](https://mediaimag.s3-us-west-2.amazonaws.com/media-3.JPG)

•	Access the app by using that endpoint , configure db with the db name.

•	For db authentication please provide username and password which are provided through terraform.tfvars file

# Expected Output

Access the application.

![alt text](https://mediaimag.s3-us-west-2.amazonaws.com/media-1.JPG)

After configuring DB.

![alt text](https://mediaimag.s3-us-west-2.amazonaws.com/media-2.JPG)

Final result

![alt text](https://mediaimag.s3-us-west-2.amazonaws.com/media-4.JPG)

