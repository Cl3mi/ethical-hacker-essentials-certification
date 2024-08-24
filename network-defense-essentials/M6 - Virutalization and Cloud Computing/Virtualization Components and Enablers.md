## Introduction to Virtualization
- **Historical Context:**
  - In the mid-1990s, companies often bought servers with large capacities (e.g., 192 GB of RAM, 20 TB storage).
  - Initially, servers were underutilized (e.g., low CPU and RAM usage) as they typically ran a single application.

## Benefits of Virtualization
- **Server Utilization:**
  - Virtualization allows multiple virtual machines (VMs) to run on a single physical server.
  - For example, one server could host DEV servers, network management functions, application servers, and database servers.
  - This consolidation led to significant reductions in data center space usage (e.g., up to 90%).

- **Impact on Data Centers:**
  - Data centers reduced space usage significantly by consolidating servers through virtualization.
  - This shift allowed for repurposing of physical space and resources.

## Virtualization Architecture
- **Traditional vs. Virtualized Architecture:**
  - Traditional: Single operating system and applications on physical hardware.
  - Virtualized: Uses a hypervisor to allow multiple operating systems and applications to run on a single physical server.

- **Virtualization Approaches:**
  - **Full Virtualization:** Complete emulation of hardware to allow multiple VMs.
  - **OS-Assisted Virtualization:** The host OS assists in virtualization.
  - **Paravirtualization:** VMs are aware of each other and the hypervisor.
  - **Hardware-Assisted Virtualization:** Uses hardware features to improve virtualization.
  - **Hybrid Virtualization:** Combines elements of the above approaches.

- **Levels of Virtualization:**
  - **Storage Virtualization:** Combining physical storage into a single virtual storage pool.
  - **File System Virtualization:** Abstracting file systems from physical storage.
  - **Server Virtualization:** Virtualizing entire servers.
  - **Network Virtualization:** Abstracting network resources and functions.

- **Types of Virtualization:**
  - **Operating System Virtualization:** Virtualizing entire operating systems.
  - **Desktop Virtualization:** Running virtual desktops on a single physical machine.

## Key Components of Virtualization
- **Hypervisor:**
  - Software that enables virtual machines to access physical hardware.
- **Virtual Machine Monitor (VMM) or Manager:**
  - Manages the allocation of resources by the hypervisor.
- **Guest Virtual Machine:**
  - Individual virtual instances of operating systems running applications.
- **Host Machine:**
  - The physical server running the hypervisor.
- **Management Server and Console:**
  - Tools for managing virtual machines and virtualization components.

## Enablers and Extensions of Virtualization
- **Network Virtualization:**
  - Networks are abstracted and managed through software, independent of physical hardware.
  - Network functions can be virtualized and distributed.

## Virtualization Vendors
- **Major Vendors:**
  - **VMware:** Dominant market share.
  - **Hyper-V:** Microsoft's virtualization solution.
  - **Citrix:** Known for virtualization solutions.
  - **VirtualBox:** Popular free virtualization platform for desktops and laptops.
  - **Virtual Iron:** Another vendor in the virtualization market.

- **Free Options:**
  - **VirtualBox:** A widely used free virtualization platform.
  - **Microsoft and VMware:** Offer free versions of their virtualization software.

## Exam
### Question 1

**Identify the virtualization approach in which the guest OS is not aware that it is running in a virtualized environment and sends commands to the virtual machine manager (VMM) to interact with the computer hardware.**

- **Full virtualization**

**Explanation:** In full virtualization, the guest operating system is unaware that it is running in a virtualized environment and interacts with the virtual machine manager (VMM) as if it were interacting directly with the hardware.

### Question 2

**In which of the following types of virtualization approach, the guest OS adopts the functionality of para virtualization and uses the VMM for binary translation to different types of hardware resources?**

- **Hybrid virtualization**

**Explanation:** Hybrid virtualization combines aspects of paravirtualization and full virtualization. It allows the guest OS to use paravirtualization techniques for efficiency while the VMM may use binary translation for handling various hardware resources.