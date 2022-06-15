---
title: "Module 2 Task 6"
linkTitle: "Task 6: Activate VMware HCX"
weight: 7

description: >
  Task 6: Activate VMware HCX
---

In this task, we will activate the On-Premises HCX appliance that we just
deployed in Task 5

1.  Browse to the On-Premises HCX Manager IP specified in Task 4 on port 9443 IP
    and login (Make sure you use **https://** in the address bar in the browser)

    1.1.  <https://10.X.Y.9:9443>

2.  Login using the **HCX Credentials** specified in Task 4

    2.1.  Username: admin

    2.2.  Password: Specified earlier in Task 4.

![](Mod2Task6Pic1.png)

Once logged in, In **Licensing**, enter your key for **HCX Advanced Key** and select **Activate**. This process can take several minutes.

![](Mod2Task6Pic2.png)

In **Datacenter Location**, provide the nearest biggest city to your location for installing the VMware HCX Manager On-Premises. Then select **Continue**. In **System Name**, modify the name to **HCX-OnPrem-XY** and click **Continue**.

![](Mod2Task6Pic3.png)

Click “**YES, CONTINUE”** for completing next task. After a few minutes HCX should be successfully activated.
