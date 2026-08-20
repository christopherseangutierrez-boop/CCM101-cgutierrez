# Identification of Cloud Infrastructure Components

## 1. Compute Resources
* **Purpose:** Process instructions, run application code, and handle active computational tasks.
* **Importance in Cloud Computing:** Compute resources form the primary engine of cloud services, allowing applications to execute dynamically without physical hardware constraints.
* **Linux Environment Context:** Represented by the virtual CPU (`Intel Xeon E312xx`) and system memory (1.9 GiB RAM) managed by the Linux kernel.

## 2. Storage Resources
* **Purpose:** Retain persistent data, configuration files, operating system files, and media.
* **Importance in Cloud Computing:** Ensures data durability, backup retention, and availability across distributed system instances.
* **Linux Environment Context:** Represented by the virtual block device `/dev/vda1` mounted at root (`/`) providing 19 GB of total disk space.

## 3. Networking Resources
* **Purpose:** Facilitate communication, routing, and data transfer between systems, services, and external networks.
* **Importance in Cloud Computing:** Enables secure cloud connectivity, load balancing, resource isolation, and internet access.
* **Linux Environment Context:** Represented by the network interfaces configured with local IP addresses (`172.30.1.2` and `172.17.0.1`) and hostname resolution.

## 4. Operating System
* **Purpose:** Manage system hardware resources, host process execution, and provide standard system tools/libraries.
* **Importance in Cloud Computing:** Acts as the foundation layer (IaaS/PaaS) hosting containers, virtual machines, and cloud services.
* **Linux Environment Context:** Represented by `Ubuntu 24.04.4 LTS` running Linux Kernel `6.8.0-138-generic`.
