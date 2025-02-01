## Jenkins Installation

1. Download and Install JDK 17
   https://download.oracle.com/java/17/archive/jdk-17.0.12_windows-x64_bin.msi

2. Download and Install Jenkins
   https://www.jenkins.io/download/thank-you-downloading-windows-installer-stable

3. Run Jenkins in Docker (in simplilearn VM)
   
   docker run -p 8081:8080 jenkins/jenkins:lts
