---
title: "Module 2 Task 3"
linkTitle: "Task 3: Import HCX's OVA"
weight: 4

description: >
  Task 3 : (Preconfigured) Import the OVA file to the On-Premises vCenter
---

In this step we will import the HCX appliance into the on premises vCenter.

You can choose to do this Task in 2 different ways:

## Option 1: Download and deploy HCX OVA to on-premises vCenter

![](Mod2Task3Pic1.png)

1. In your AVS Private Cloud blade click **Identity**.
2. Locate and save both vCenter admin username **cloudadmin@vsphere.local** and password.

![](Mod2Task3Pic2.png)

1. Click on **+ Add-ons**.
2. Copy the **HCX Cloud Manager IP**.

![](Mod2Task3Pic3.png)

From your Jumpbox, open a browser tab and paste the **HCX Cloud Manager IP** and enter the credentials obtained in the previous step.

![](Mod2Task3Pic4.png)

1. In the left pane click **System Updates**.
2. Click **REQUEST DOWNLOAD LINK**, please keep in mind that the button might take a couple of minutes to become enabled.

![](Mod2Task3Pic5.png)

1. Click **VMWARE HCX** to download the HCX OVA to complete this option.
2. You can also click **COPY LINK** if you will install HCX with Option 2.

## Option 2: Deploy HCX from a vCenter Content Library

>**NOTE: An older copy of HCX exists already in the Content Library. Feel free to download and use the newer version through the steps above**

From the Jumpbox, browse to the On-Premises vCenter URL, See [Getting Started](getting-started#on-premises-vmware-lab-environment) section for more information and login details.

![](f0521b4c3bb4b3a7207f9b24e01a2620.png)

1. From your on-premises vCenter click **Menu**.
2. Click **Content Libraries**.

3.  Create a new content library if one doesn’t exist

4.  Once done, select Actions \> Import Item

5.  Enter HCX URL copied from Task 3, Step 6

    ![](aa0df7163b5265bbb9b5dffe036f1797.png)

6.  Accept any prompts and actions and proceed. The HCX OVA will download to the
    library in the background

