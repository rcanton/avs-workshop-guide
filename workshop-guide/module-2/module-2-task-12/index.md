---
title: "Module 2 Task 12"
linkTitle: "Task 12: Network Extension"
weight: 13

description: >
  Task 12: Setup the Network Extension
---


Once the Service Mesh appliances have been deployed, the next important step is
to extend the on-premise network to AVS, so that any migrated VM’s will be able
to retain their existing IP address and be accessible from all locations

1.  Navigate to **Network Extension,** Create a Network Extension

    ![](f9faed0da1836acad9fcfea26682da5a.png)

2.  Select the service mesh and segment to extend. In this lab, we will extend
    **workload-web**

    ![](4279fd1dd752bcb12e57d5d44c8725a1.png)

3.  Select the First Hop Router, in this Lab there is only 1 option –
    **TNTXX-TI**

4.  Enter the Workload Web Gateway IP as 10.**X**.10**Y**.1/25.

    ![](e9731ade07f7a8bf3ee8172fc72ae6b6.png)

5.  Submit, this will start the process of extending the network by creating a
    remote stretch record and network bridges on the remote AVS side. This will
    take about 3-5 minutes to complete

    ![](41ee30763f7c89fcfe7c427d25d12837.png)

