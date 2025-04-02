# UL Lab workbook

## Lab Environment Overview
The lab scenarios will be deployed and executed in a virtual environment. The environment can be built directly from the student’s own computer or UL server if preferable, however, the exercises are designed to be run on Github Codespaces to streamline the process.

The virtual environment will leverage Containerlab platform to run containerized instances of Arista EOS software. This presents an advantage in comparison to the use of virtual machines as containers (cEOS-lab) represent a lightweight solution, not requiring a full OS for each instance.

## Containerlab
Containerlab is a lightweight and flexible network emulation tool that enables users to build and manage container-based networking labs. It is designed to simplify the deployment of network topologies using containerized network operating systems (NOS) and virtualized network functions (VNFs).

## Arista Networks, Arista EOS and cEOS-lab
Arista Networks is a leading provider of cloud networking solutions for data centers, cloud service providers, and enterprise environments. Founded in 2004, the company specializes in high-performance, programmable, and highly scalable network architectures. Arista's networking solutions focus on automation, open standards, and software-driven networking, making them popular for cloud computing, SDN, and AI workloads.

https://www.arista.com/en/company/company-overview 

Arista EOS (Extensible Operating System) is the network operating system (NOS) that powers Arista's switches and routers. Unlike traditional monolithic NOS architectures, EOS is built on a Linux-based, fully modular architecture, offering:
Single Binary Image: Ensures a consistent software experience across all Arista platforms.
Programmability & Automation: Provides open APIs, including CLI, eAPI (RESTful API), and gNMI.
High Stability: A modular architecture where failures in one component do not affect the entire system.
Cloud-Scale Performance: Designed for high-throughput, low-latency networking in data centers and cloud environments.
EOS supports SDN integration, telemetry, EVPN/VXLAN, and high-performance routing, making it suitable for modern cloud-based and data center networks.

https://www.arista.com/en/products/eos

## Arista cEOS-lab (Containerized EOS) is a containerized version of Arista EOS, designed for virtualized network labs, testing, and automation development. Instead of running EOS on dedicated hardware, cEOS-lab runs as a lightweight container, making it ideal for:
Network Emulation: Deploy Arista EOS instances in Containerlab, Docker, or Kubernetes.
CI/CD & DevOps Integration: Allows automated testing and validation of network configurations.
SDN and Network Automation: Provides an API-driven, programmable network platform for SDN research and development.
Lightweight and Portable: Can be deployed on a single Linux machine, enabling network engineers and students to experiment with Arista's network OS without requiring physical hardware.

Download cEOS-lab:
- Register on our website for free (University email can be used, public domains such as google, outlook, etc. not allowed))
  https://www.arista.com/en/user-registration
- Download cEOS-lab
  https://www.arista.com/en/support/software-download

## Getting started with the labs
