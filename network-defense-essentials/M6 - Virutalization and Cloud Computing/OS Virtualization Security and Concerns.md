### OS Virtualization
- **Traditional Virtualization**: Involves running a full operating system (OS) on a hypervisor, which allocates hardware resources like CPU and RAM to virtual machines (VMs). Multiple applications run on these VMs.
- **Purpose**: Virtualization aims to make applications available, but applications do not necessarily need a full OS to operate.

### Containerization
- **Concept**: Containers isolate applications and provide only the resources they need. This is more efficient than virtualizing an entire OS.
- **Advantages**: Containers are lightweight, share the host OS, and require less memory compared to VMs.

## Container Technology

### Key Components
- **Container Engine**: Manages the runtime environment for containers.
- **Container Orchestration**: Automates the deployment, scaling, and management of containerized applications. Examples include Docker Swarm, OpenShift, and Kubernetes.

### Container Architecture
1. **Image Creation**:
   - Developers create and test container images.
   - Images are stored in registries (both internal and external).
2. **Deployment and Management**:
   - Containers are deployed across multiple hosts.
   - Orchestrators automate the lifecycle management of containers.

### Types of Containers
- **OS Containers**:
  - Contain an entire OS.
  - Tools: LXC, OpenVz, Linux-Vserver, BSD Jails, Solaris Zones.
- **Application Containers**:
  - Contain a single application and its dependencies.
  - Tools: Docker, Rocket.

## Comparison: Containers vs. Virtual Machines (VMs)
- **Containers**:
  - **Lightweight**: No full OS required.
  - **Memory Usage**: Lower, as containers share the host OS.
  - **Isolation**: Process-level isolation.
  - **Management Tools**: Docker, LXC, LXD.
- **VMs**:
  - **Full OS Required**: Each VM runs its own OS.
  - **Memory Usage**: Higher, due to multiple OS instances.
  - **Isolation**: Complete isolation with a hypervisor.
  - **Management Tools**: VMware, Hyper-V, vSphere, VirtualBox.

## Docker

### Key Features
- **Platform**: Open-source, OS-level virtualization.
- **Components**:
  - **Docker Daemon**: Runs in the background, manages containers.
  - **Docker Client**: Interface for interacting with Docker.
  - **Docker Engine**: Manages containers and images.
- **Docker Networking**:
  - **Container Network Model (CNM)**: Facilitates application portability across heterogeneous infrastructure.

## Kubernetes (K8s)

### Overview
- **Purpose**: Orchestrates containerized applications and microservices, providing resilience, automation, and distribution.
- **Components**:
  - **Kube Master**: Manages the cluster.
  - **Nodes**: Run containers and communicate with the Kube Master.
  - **Other Components**: API Server, Scheduler, etcd, Cloud-Controller Manager.

## Security Concerns

### General Container Security Issues
- **Vulnerable Source Code**: Risk from insecure code.
- **Large Attack Surface**: Multiple containers increase vulnerability.
- **Lack of Visibility**: Difficulty in monitoring container activities.
- **Secrets Management**: Secure storage of sensitive information (e.g., private keys).

### Specific Security Threats
- **Noisy Neighbor Containers**: Containers consuming excessive resources.
- **Container Escape**: Attackers breaking out of containers to access the host system.
- **Network-Based Attacks**: Attacks targeting containerized applications through the network.
- **Image Threats**: Vulnerabilities in container images or embedded malware.
- **Registry Threats**: Security issues related to image registries and secure connections.
- **Runtime Configuration Issues**: Poorly configured container runtimes.

### Docker-Specific Threats
- **Root Access**: Unauthorized access to Docker containers.
- **DDoS Attacks**: Distributed denial-of-service attacks targeting Docker.
- **Unpatched Exploits**: Attacks on unpatched Docker vulnerabilities.

### Kubernetes-Specific Threats
- **East-West Traffic Exploitation**: Risks from internal traffic within the Kubernetes cluster.
- **Automated Security Management**: Challenges in managing security across many containers.
- **Default Configuration Settings**: Risks associated with default settings.
- **Runtime Security Challenges**: Issues with running applications and binaries.

## Exam
- **Question 1**: Which of the following types of service enables the deployment of containers and container management through orchestrators and using which subscribers can develop rich, scalable containerized applications through the cloud or on-site data centers?
    - **CaaS (Container as a Service)**

- **Question 2**: Which of the following components in a Kubernetes cluster architecture is a backing store for the data in the Kubernetes cluster?
    - **Etcd**
- 