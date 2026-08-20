# Laboratory 2: Build the Cloud Infrastructure Blueprint

## Mission Overview
Investigated the components of cloud infrastructure using a Linux environment, evaluated foundational cloud resources, compared major cloud providers (AWS, Azure, GCP), and designed an initial cloud architecture blueprint.

## Objectives
* Explain major components of cloud infrastructure.
* Investigate hardware and software resources in a Linux environment.
* Differentiate compute, storage, networking, and identity resources.
* Compare services across AWS, Azure, and GCP.
* Create technical documentation using Markdown.

## Cloud Infrastructure Components
* **Compute:** Intel Xeon CPU (1 core), 1.9 GiB RAM
* **Storage:** 19 GB Virtual Disk (`/dev/vda1`)
* **Networking:** IP addresses `172.30.1.2` / `172.17.0.1`
* **OS:** Ubuntu 24.04.4 LTS (Kernel 6.8.0-138-generic)

## Tools Used
* KillerCoda Playground (Ubuntu Linux Environment)
* Git & GitHub
* Diagramming Tool (Excalidraw / Draw.io)

## Linux Commands Executed
* `uname -r`, `cat /etc/os-release`
* `lscpu | grep -E "Model name|CPU\(s\):"`
* `free -h`, `df -h /`
* `hostname`, `hostname -I`

## Skills Learned
* Shell inspection of system resources.
* Mapping physical/virtual Linux primitives to cloud services.
* Service equivalency mapping across AWS, Azure, and GCP.

## Challenges Encountered
* Managing root vs. non-root file ownership and Git safe directory configurations.
* Synchronizing local terminal changes with remote GitHub commits after web updates.