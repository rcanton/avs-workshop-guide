---
title: "Module 4 Task 1"
linkTitle: "Task 1: Virtual WAN"
weight: 2

description: >
  Module 4:  Deploy Virtual WAN
---


1.  Sign into the Azure portal and then search for and select Azure VMware
    Solution.

2.  Select the Azure VMware Solution private cloud.

3.  Under Manage, select Connectivity.

4.  Select the Public IP tab and then select Configure.

    ![](940de2ea4f975fdd88235093f29267f1.png)

5.  Accept the default values, modify the Virtual hub address block and Number
    of Public Ips fields. Select Create.

    | Field                         | Value                                                                                                                 |
    |-------------------------------|-----------------------------------------------------------------------------------------------------------------------|
    | Virtual WAN resource group    | Auto-populated and can not be modified in the poral                                                                   |
    | Virtual WAN name              | Leave default auto-populated                                                                                          |
    | Virtual hub address block     | Use the following value 10.**XY**.4.0/24 to avoid conflict with other networks used in this training |
    | Number of public IPs (1-100): | 1                                                                                                                     |

    ![](6295fbcd7f543b20d04c2dbdfb5bf43e.png)

    It takes about one hour to complete the deployment of all components. This
    deployment only must occur once to support all future public IPs for this Azure
    VMware Solution environment.

    ![](7edc575f5739614c0749fc11eefb53c4.png)
