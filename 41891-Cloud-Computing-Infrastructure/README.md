# 41891: Cloud Computing Infrastructure

This folder contains a collection of projects and lab write-ups from the Cloud Computing Infrastructure course, a core component of my Bachelor of Cybersecurity degree at UTS. This subject provided extensive, hands-on experience in designing, implementing, and managing a virtualised data center from the ground up using industry-standard VMware vSphere technologies.

The projects documented here showcase the end-to-end process of building a scalable and resilient IaaS (Infrastructure as a Service) environment.

---

## Core Competencies Developed

Through these labs, I gained practical proficiency in the following key areas of cloud and virtualisation technology:

*   **Hypervisor Management:**
    *   Installation and configuration of a Type-1 hypervisor (VMware ESXi).
    *   Direct host management via the ESXi Host Client and Direct Console User Interface (DCUI).

*   **Centralised Infrastructure Management:**
    *   Deployment and administration of vCenter Server Appliance (VCSA) for unified control over multiple hosts.
    *   Creation and management of Datacenter and Cluster objects.

*   **Advanced Storage & Networking:**
    *   Configuration of shared storage using **iSCSI** to create a Storage Area Network (SAN).
    *   Creation of clustered **VMFS** datastores.
    *   Implementation of virtual networking with vSphere Standard Switches, Port Groups, and **VLANs** for traffic segmentation and security.

*   **Business Continuity & Performance:**
    *   Execution of live migrations (**vMotion** and **Storage vMotion**) to perform maintenance with zero downtime.
    *   Configuration of **vSphere High Availability (HA)** to provide automated failover in the event of a host failure.
    *   Implementation of **Resource Pools** to manage and guarantee CPU and memory resources for critical applications.

---

## Lab Projects Overview

Each lab represents a key building block of the final infrastructure. Click on a lab to view a detailed write-up of the objectives, procedures, and core concepts demonstrated.

*   **[Lab 1: ESXi Installation and VM Deployment](https://github.com/shayanxcyber/VMware-vSphere-Lab-Projects/tree/main/Lab-01-ESXi-and-VM-Deployment)**
    *   *Focus: Installing a Type-1 hypervisor and deploying a guest VM.*

*   **[Lab 2: iSCSI Shared Storage Configuration](https://github.com/shayanxcyber/VMware-vSphere-Lab-Projects/tree/main/Lab-02-iSCSI-Storage-Configuration)**
    *   *Focus: Connecting ESXi hosts to a central SAN using the iSCSI protocol.*

*   **[Lab 3: vCenter Server Deployment and vMotion](https://github.com/your-username/VMware-vSphere-Lab-Projects/tree/main/Lab-03-vCenter-Server-and-vMotion)**
    *   *Focus: Centralising management with VCSA and performing live VM migrations.*

*   **[Lab 4: vSphere Standard Switches and VLANs](https://github.com/your-username/VMware-vSphere-Lab-Projects/tree/main/Lab-04-vSwitches-and-Port-Groups)**
    *   *Focus: Creating logically isolated networks using VLANs for security and segmentation.*

*   **[Lab 5: vSphere Clusters, Resource Pools, and HA](https://github.com/your-username/VMware-vSphere-Lab-Projects/tree/main/Lab-05-Resource-Pools-and-HA)**
    *   *Focus: Aggregating host resources and configuring automated failover with High Availability.*
