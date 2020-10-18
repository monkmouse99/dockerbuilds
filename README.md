# Docker Builds
This repo will host build files, scripts and related documentation for a DevOps environment based on the following toolset with the focus on Linux/Windows.
   * Docker 
   * Jenkins with Docker integration and agent templates
   * Python (optional) used primarily for testing
   
# Super Awesome Tutorials from the Inter-Web
  * Maxfield Stewart's well written post on Riot Games - [Tutorial](https://technology.riotgames.com/news/jenkins-ephemeral-docker-tutorial)
  * Phillip Edwards excellent 4-part series on setting up a Jenkins Home Lab - [Part 1](https://www.gdcorner.com/2019/12/27/JenkinsHomeLab-P1-MasterSetup.html)
  * Tom Gregory's concise article on Running Docker on Windows - [Here](https://tomgregory.com/running-docker-in-docker-on-windows/)
  
# Primary Use Case: Build a Docker/Jenkins Environment
1. Architectural Overview 
    * Option 1: All-in-one-build on development box using localhost and */var/run/docker.sock*
        * Placeholder for Ubuntu Jenkins/Docker setup on the same box
        * Placeholder for Windows Jenkins/Docker setup on the same box
        * Placeholder for Raspberry Pi Jenkins/Docker setup on the same box
    * Option 2: Distributed build with one central Jenkins master and multiple Docker clouds 
        using *tcp://server:port* 
        * Placeholder for master Windows Jenkins/Docker server with distributed Docker clouds on various OS
        * Placeholder for master Ubuntu Jenkins/Docker server with distributed Docker clouds on various OS
        * Placeholder for master Raspberry Pi Jenkins/Docker server with distributed Docker clouds on various OS
2. Documentation on Docker setup with links to official documentation
    * Overview and resources
3. Documentation on Jenkins with links to official documentation 
    * Overview and resources
         * [Jenkins installation on Docker official documentation](https://github.com/jenkinsci/docker/blob/master/README.md)
4. Setup Docker plug-ins for Jenkins to setup Docker Cloud
5. Jenkins Master / Agent Resources and Docker Agent Templates
6. JNLP vs SSH Resources
   * Configure Docker agent templates with JNLP
   * Configure Docker agent templates with SSH
7. Testing Agents 
