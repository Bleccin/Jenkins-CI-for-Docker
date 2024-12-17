# Jenkins-CI-for-Docker

Project scope: create a Declarative Jenkinsfile  for a CI pipeline.

Overview of Jenkinsfile:
1. Fetch code from Github.
2. Perform 'Unit Test' with Maven.
4. perform 'Code Analysis' with Checkstyle.
5. perform another 'Code Analysis' with SonarQube.
6. Build Docker image with the Artifact.
7. Publish the Docker Image to Amazon ECR.

   Steps:
   AWS
1. Install AWS CLI.
2. Create an IAM USER with Access Keys.
3. Create an Amazon ECR Registry for the Docker image.

   Jenkins
4. Install Docker and Docker pipeline plugins.
5. Install ECR plugin.
6. Install AWS SDK.
7. Add Docker user to docker group & reboot.
8. Store  AWS access keys(credentials).
9. Install Docker Engine in Jenkins.

10. Run the pipeline.
