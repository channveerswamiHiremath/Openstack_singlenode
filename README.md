# Single-Node Private Cloud Using OpenStack, Kolla-Ansible, Swift, Nextcloud and Tailscale

## Overview

This project focuses on building and deploying a self-hosted private cloud infrastructure using OpenStack on a single-node environment.

The infrastructure was deployed using Kolla-Ansible, which automates the deployment and management of OpenStack services through Docker containers.

The implementation provides a private cloud environment for managing virtual machines, networking and storage resources. OpenStack Swift was configured for object storage, while Nextcloud was integrated to provide a user-friendly cloud storage interface. Tailscale was used to enable secure remote access to the environment.

The project demonstrates practical implementation of cloud infrastructure, virtualization, containerization, software-defined networking and private cloud storage.

## Architecture

The deployment consists of the following components:

- **Infrastructure Layer:** Ubuntu Server 22.04 running in a VirtualBox virtual machine.
- **Deployment Layer:** Kolla-Ansible for automated OpenStack deployment.
- **Containerization Layer:** Docker for running OpenStack services.
- **Compute Layer:** OpenStack Nova for virtual machine provisioning.
- **Networking Layer:** OpenStack Neutron for virtual networking and connectivity.
- **Identity Layer:** OpenStack Keystone for authentication and authorization.
- **Image Layer:** OpenStack Glance for virtual machine images.
- **Storage Layer:** OpenStack Swift for object storage.
- **Cloud Storage Interface:** Nextcloud for file management and access.
- **Remote Access:** Tailscale for secure connectivity.

## Technologies Used

| Technology | Purpose |
|---|---|
| Ubuntu Server 22.04 | Host operating system |
| OpenStack | Private cloud platform |
| Kolla-Ansible | OpenStack deployment automation |
| Docker | Container runtime |
| Ansible | Infrastructure automation |
| Nova | Compute and VM management |
| Neutron | Networking |
| Keystone | Identity and authentication |
| Glance | Image management |
| Swift | Object storage |
| Nextcloud | Cloud storage interface |
| Tailscale | Secure remote access |
| VirtualBox | Virtualization environment |

## Key Features

- Single-node OpenStack private cloud deployment.
- Automated deployment using Kolla-Ansible.
- Containerized OpenStack services using Docker.
- Virtual machine provisioning and management.
- Software-defined networking using Neutron.
- Image management using Glance.
- Identity and access management using Keystone.
- Object storage using OpenStack Swift.
- Nextcloud integration for centralized file management.
- Secure remote connectivity using Tailscale.

## Implementation

### 1. Infrastructure Preparation

- Created an Ubuntu Server 22.04 virtual machine using VirtualBox.
- Allocated CPU, RAM and storage resources.
- Configured the required network interfaces.
- Prepared the environment for OpenStack deployment.

### 2. Kolla-Ansible Installation

- Installed Kolla-Ansible and its dependencies.
- Configured Ansible inventory.
- Prepared global configuration and deployment variables.
- Configured Docker as the container runtime.

### 3. OpenStack Deployment

- Configured the required OpenStack services.
- Executed the Kolla-Ansible bootstrap and deployment procedures.
- Deployed OpenStack services as Docker containers.
- Verified service availability and dashboard access.

### 4. Compute and Networking Configuration

- Configured Nova for virtual machine provisioning.
- Configured Neutron networking.
- Created virtual networks, subnets and routers.
- Configured external connectivity.
- Verified virtual machine network connectivity.

### 5. Swift Object Storage

- Configured OpenStack Swift for object storage.
- Prepared storage devices for the Swift environment.
- Configured storage policies and object containers.
- Verified object upload and retrieval operations.

### 6. Nextcloud Integration

- Deployed Nextcloud using Docker.
- Configured the cloud storage integration with OpenStack Swift.
- Configured the required storage access.
- Verified file management through the Nextcloud interface.

### 7. Remote Access Using Tailscale

- Installed and configured Tailscale.
- Connected the private cloud environment to the Tailscale network.
- Verified remote access from authorized devices.

## Challenges and Solutions

The deployment involved working with multiple infrastructure components, including containerized services, networking and storage.

Key areas addressed during implementation included:

- Resolving Docker permission and container deployment issues.
- Configuring Ansible dependencies required by Kolla-Ansible.
- Managing virtual machine resources during deployment.
- Configuring network interfaces and external connectivity.
- Preparing storage devices for OpenStack storage services.
- Integrating Swift with Nextcloud.
- Establishing secure remote connectivity.

## Results and Outcomes

The project successfully demonstrated:

- Deployment of a single-node OpenStack private cloud.
- Automated infrastructure deployment using Kolla-Ansible.
- Containerized OpenStack service management.
- Virtual machine provisioning and networking.
- Object storage configuration using Swift.
- Integration of Nextcloud with private cloud storage.
- Secure remote access using Tailscale.

## Learning Outcomes

- OpenStack architecture and service integration.
- Automated cloud deployment using Kolla-Ansible.
- Docker-based infrastructure management.
- Linux server administration.
- Virtualization and compute resource management.
- Software-defined networking.
- Object storage architecture and management.
- Private cloud storage integration.
- Secure networking and remote access.

## Project Demonstration

A screen-recorded demonstration of the deployed private cloud environment is available below.

**[Watch the Single-Node OpenStack Project Demonstration](https://github.com/channveerswamiHiremath/Openstack_singlenode/blob/main/Video_exp.mp4)**

*Note: The demonstration is a silent screen recording showing the actual implementation and working environment.*

## Documentation

Detailed project documentation, including deployment procedures, configuration and implementation screenshots:

**[View Project Documentation (PDF)]OpenStack_documentation.pdf**

## Conclusion

This project demonstrates the deployment of a private cloud infrastructure using OpenStack and Kolla-Ansible in a single-node environment. By integrating compute, networking, identity and object storage services with Nextcloud and Tailscale, the implementation provides a foundation for a self-hosted cloud environment.

The project provided hands-on experience in cloud infrastructure deployment, Linux administration, containerization, software-defined networking and storage integration.

---

**Technologies:** OpenStack | Kolla-Ansible | Docker | Ansible | Ubuntu Server | Nova | Neutron | Keystone | Glance | Swift | Nextcloud | Tailscale
