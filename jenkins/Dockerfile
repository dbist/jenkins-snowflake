FROM jenkins/jenkins:lts

# Install required applications
USER root
RUN apt-get update
RUN apt-get install -y docker.io
RUN usermod -aG docker jenkins

# Drop back to the regular jenkins user
USER jenkins
