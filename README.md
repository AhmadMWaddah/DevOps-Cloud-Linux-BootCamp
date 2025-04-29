# **DevStack on KVM: OpenStack Cloud Lab for DevOps & Linux Administration**  

## **📌 Project Overview**  
This project documents the setup of a **production-like OpenStack cloud environment** using **DevStack** inside an **Ubuntu Server 22.04 virtual machine**, hosted on **KVM/QEMU** (Ubuntu 24.04 host). The goal is to create a **hands-on lab** for practicing:  

- **Linux system administration** (KVM, networking, storage)  
- **OpenStack cloud deployment & management** (Nova, Neutron, Cinder, Horizon)  
- **Infrastructure automation** (Terraform, Ansible)  
- **DevOps workflows** (CI/CD, monitoring, logging)  

The environment will be used to **spin up additional VMs** for testing configurations, deploying applications, and simulating real-world cloud operations.


![Display Me](https://github.com/AhmadMWaddah/DevOps-Cloud-Linux-BootCamp/blob/master/AMW%20DevOps%20DevStack%20Linux.jpeg)

---

## **🔧 Technical Stack**  

| **Component**       | **Technology Used**          | **Purpose** |
|---------------------|-----------------------------|-------------|
| **Host OS**         | Ubuntu 24.04 LTS            | Base system running KVM |
| **Virtualization**  | KVM/QEMU + libvirt          | VM management |
| **Guest OS**        | Ubuntu Server 22.04 LTS     | DevStack deployment |
| **Cloud Platform**  | DevStack (OpenStack)        | All-in-one OpenStack cloud |
| **Automation**      | Bash, Terraform, Ansible    | Infrastructure as Code (IaC) |
| **Networking**      | NAT + OpenStack Neutron     | Virtual networking for VMs |

---

## **🎯 Lab Objectives**  

### **1. KVM Host Setup**  
✔️ Install & configure **KVM/QEMU** on Ubuntu 24.04  
✔️ Set up **NAT networking** for guest VMs  
✔️ Deploy **Ubuntu Server 22.04** as a KVM guest  

### **2. DevStack (OpenStack) Deployment**  
✔️ Install **DevStack** (all-in-one OpenStack)  
✔️ Configure **Horizon dashboard** (web UI)  
✔️ Verify **Nova (compute), Neutron (networking), Cinder (storage)**  

### **3. OpenStack VM Management**  
✔️ Upload **cloud images** (Ubuntu, CentOS)  
✔️ Launch **nested VMs** via OpenStack  
✔️ Test **floating IPs, security groups, volumes**  

### **4. Automation & DevOps Integration**  
✔️ **Terraform** for OpenStack resource provisioning  
✔️ **Ansible** for VM configuration management  
✔️ **CI/CD pipeline** (Jenkins/GitHub Actions)  

---
---

## **🚀 Roadmap (Future Enhancements)**  

| **Phase**       | **Tasks** |
|----------------|-----------|
| **Phase 1**    | ✅ KVM Host Setup <br> ✅ Ubuntu Server 22.04 VM <br> ✅ DevStack Deployment |
| **Phase 2**    | 🔄 OpenStack VM Management <br> 🔄 Terraform Automation |
| **Phase 3**    | 🔜 Ansible Configuration <br> 🔜 CI/CD Integration |
| **Phase 4**    | 🔜 Monitoring (Prometheus/Grafana) <br> 🔜 Logging (ELK Stack) |

---

## **📝 How to Use This Project**  

1. **Follow the [documentation](/docs/)** for step-by-step setup.  
2. **Report issues** for troubleshooting.  
3. **Contribute** by improving automation scripts.  
4. **Extend the lab** with Kubernetes, CI/CD, or monitoring.  

---

## **💡 Why This Lab?**  
- **Real-world cloud experience** (OpenStack is used in private clouds)  
- **Improve Linux & networking skills** (KVM, NAT, bridges)  
- **Learn Infrastructure as Code (IaC)** (Terraform, Ansible)  
- **Prepare for DevOps/Cloud roles** (Hands-on OpenStack practice)  
