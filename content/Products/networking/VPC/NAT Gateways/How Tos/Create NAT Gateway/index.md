---
weight: 40
title: "Create NAT Gateway"
title_meta: "Create NAT Gateway"
description: "Guide on how to create nat gateway in utho cloud platform"
keywords: ["cloud", "instances",  "ec2", "server", "graph"]
tags: ["utho platform","cloud"]
date: "2024-03-07T17:25:05+01:00"
lastmod: "2024-03-07T17:25:05+01:00"
draft: false
toc: true
aliases: ["/products/networking/VPC/NAT Gateways/How Tos/Create NAT Gateway"]
icon: "globe"
tab: true
---



## **How to Create NAT Gateway in Utho Cloud**

### **Overview**

Creating a NAT Gateway in Utho Cloud enables resources in private subnets to access the internet securely while keeping them shielded from direct inbound internet traffic. This guide will walk you through the process of creating a new NAT Gateway, including configuring its name, subnet, and Elastic IP allocation.

### **1. Navigate to the NAT Gateway Listing Page**

* On the left sidebar of the platform, find the **VPC** menu.
* Under the **VPC** section, select  **NAT Gateways** .
* Clicking on **NAT Gateways** will take you to the  **NAT Gateway Listing Page** , where you can view all the existing NAT Gateways.

Alternatively, you can directly access the NAT Gateway listing page by clicking this [link to NAT Gateway Listing](https://conjsole.utho.com/vpc/natgateways).

---

### **2. Create a New NAT Gateway**

At the top of the  **NAT Gateway Listing Page** , you'll find a button labeled  **"Create NAT Gateway"** . Clicking this button will open a configuration drawer where you'll need to enter several details for the new NAT Gateway.

![1744179499936](image/index/1744179499936.png)

---

### **3. Configure the NAT Gateway**

In the configuration drawer, you'll be prompted to provide the following information for the new NAT Gateway:

1. **Name** :

* This field allows you to provide a **name** for your NAT Gateway. It is used to uniquely identify the gateway within your account and helps you manage and reference it later.

2. **Subnet** :

* This is a **dropdown** menu where you can select the **subnet** to which the NAT Gateway will be attached. Only available subnets will be shown here, and you can choose one based on the location and configuration of your resources.

3. **Elastic IP Allocation ID** :

* This dropdown allows you to select an **Elastic IP** that has been allocated previously. If there are no Elastic IPs available, a button labeled **"Allocate IP"** will be shown next to the dropdown. Clicking on this button will generate and allocate a new Elastic IP for the NAT Gateway, which will then be available for selection in the dropdown.

![1744179591360](image/index/1744179591360.png)

---

### **4. Create the NAT Gateway**

Once all the configuration inputs have been filled, click on the **"Create NAT Gateway"** button. This will initiate the creation of the NAT Gateway with the specified settings.

---

### **5. Verify NAT Gateway Creation**

After the NAT Gateway has been created, you’ll be redirected back to the  **NAT Gateway Listing Page** , where you can verify that your newly created NAT Gateway is listed with the provided details. You can now manage the NAT Gateway as needed.

![1744179658306](image/index/1744179658306.png)

---

### **Conclusion**

Creating a NAT Gateway in Utho Cloud is a straightforward process that allows your private subnet resources to securely access the internet. By following these steps, you can easily configure the name, subnet, and Elastic IP for your new NAT Gateway. Once created, you can verify and manage the NAT Gateway from the listing page.
