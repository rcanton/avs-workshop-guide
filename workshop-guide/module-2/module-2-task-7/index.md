---
title: "Module 2 Task 7"
linkTitle: "Task 7: Configure HCX"
weight: 8

description: >
  Task 7: Configure HCX and connect to vCenter
---

In this section, we will integrate HCX Manager with the On-Premises vCenter

1.  In **Connect your vCenter**, provide the FQDN or IP address of on-premise
    vCenter server and the appropriate credentials, and then select
    **Continue**., see Getting Started Section for more details

    1.1.  In this lab, this is <https://10.X.Y.2>

    1.2.  Username:
        [administrator@vsphere.local](mailto:administrator@vsphere.local)

    1.3.  Password: 0hDG3VqFyTd!

    ![](0a34329d4d0c9980b0d59faf964df212.png)

2.  In **Configure SSO/PSC**, provide the same vCenter IP address, and select
    **Continue**.

    2.1.  https://10.X.Y.2

    ![](5a9f978cbd67220a76f703daf0a27a58.png)

3.  Verify that the information entered is correct and select **Restart**.

    ![](56d1acedec32851aff081d76449169e1.png)

    The restart may take up to 10 minutes

4.  After the services restart, you'll see vCenter showing as **Green** on the
    screen that appears. Both vCenter and SSO must have the appropriate
    configuration parameters, which should be the same as the previous screen.

    ![](d9c3ff0b3daed977841b865b30fb338d.png)

    > **Note**: It may take an additional 5-10 minutes for the HCX plugins to be
    installed in vCenter, log back out and log back in if it does not show up
    automatically