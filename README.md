# Jenkins-Sonar-Nexus-Tomcat-project
Configured Jenkins, Nexus, SonarQube, and Tomcat for a Full CI/CD Pipeline on AWS EC2!

**Key Achievements:**
**EC2 Setup:**
- Jenkins (8080) and SonarQube (9000) on T2.medium with 30GB EBS volume.
- Tomcat (8080) on T2.micro
- Nexus (8081) on a separate T2.medium with 30GB EBS volume.

**Jenkins Configuration:**
- Scripted pipeline and essential plugins for automation.
- Installed plugins for SonarQube scanner, Deploy to Container, and Nexus artifact.
- Set up Git, Java, and Maven.
- Configured Jenkins to run on port 8080 for continuous integration.

**Nexus Configuration:**
- Installed and configured Nexus for efficient artifact management.

**SonarQube Configuration:**
- Installed SonarQube on port 9000.
- Generated a security token for SonarQube integration.
- Configured SonarQube in Jenkins for automatic code quality analysis.

**Pipeline Workflow:**
- Configured GitHub repository URL in Jenkins for automatic builds upon changes.
- Automated artifact uploads and deployments with Jenkins and Nexus.
- Implemented SonarQube quality checks in Jenkins to ensure high code quality before deployment.


![image](https://github.com/user-attachments/assets/3e4b0f78-77d1-4117-b0d6-0216d309307f)
![image](https://github.com/user-attachments/assets/9e9912ef-065f-48e9-9201-10494da07dc1)

