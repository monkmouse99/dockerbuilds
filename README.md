# Docker Builds
This repo will host build files, scripts and related documentation for a DevOps environment based on the following toolset with the focus on Linux/Windows.
   * Docker 
   * Jenkins with Docker integration and agent templates
   * Python (optional)

# Primary Use Case: Build a Docker/Jenkins Environment
1. Architectural Overview 
    * Option 1: All-in-one-build on development box 
    * Option 2: Distributed build
         * Development station using /var/run/docker.sock for Jenkins Docker Plug-in
         * Dedicated Docker/Jenkins server/workstation using tcp://server:port for Jenkins Docker Plug-in
2. Documentation on Docker setup with links to official documentation
    * Overview and resources
3. Documentation on Jenkins with links to official documentation 
    * Overview and resources
4. Setup Docker plug-ins for Jenkins to setup Docker Cloud
5. Jenkins Master / Agent Resources and Docker Agent Templates
6. JNLP vs SSH Resources
   * Configure Docker agent templates with JNLP
   * Configure Docker agent templates with SSH
7. Testing Agents 
