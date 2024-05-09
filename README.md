# CICD-Project 


The code hosted on GitHub will undergo a quality check with SonarQube and dependency verification using OWASP’s tools. For security scanning of Docker images, Trivy will be utilized. The deployment of the Docker container and the automation of these processes will be managed through Jenkins.

Code should be sent from Jenkins to SonarQube for analysis and the analyzed code should be received by Jenkins . This can be done through webhook token for authentication (Integrating Jenkins and SonarQube). 
OWASP has libraries/packages and Jenkins requires a dependency check which can be fully filled by OWASP from Jenkins Tools Section. 
