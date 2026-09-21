# 💬 Mission 04 Reflection & Critical Analysis

> **Author:** Christopher Sean Gutierrez  
> **Role:** Cloud-Native Engineer  

Deploying a Docker container highlights a massive speed advantage when compared to traditional Virtual Machines. Installing an operating system on a VM involves hypervisor overhead, full OS initialization, and multi-minute boot cycles . In contrast, Docker containers share the host operating system kernel, enabling applications like Nginx to launch instantly within seconds .

Port mapping (`-p 8080:80`) is necessary because containers run in isolated network namespaces separated from the host system . Port 80 is internal to the container; mapping it to host port 8080 creates a network bridge, allowing external users and local host tools like `curl` to reach the containerized web service .

When executing the `docker rm` command, the writable container layer and its temporary filesystem are permanently destroyed . Any un-vaulted data generated inside the container during runtime is lost unless bound to persistent external Docker Volumes or host bind mounts .

Containerization fundamentally transforms DevOps collaboration by solving the "works on my machine" problem. Software developers package application code, dependencies, and configurations into standardized container images . IT operations teams can then deploy these identical container images across development, testing, and multi-cloud production environments without compatibility issues .

Finally, my GitHub Cloud Computing Portfolio is evolving from basic IaaS infrastructure assessments to modern cloud-native engineering techniques . Adding containerization workflows, lifecycle commands, and architectural comparison matrices demonstrates practical competence in cloud development and DevOps practices .