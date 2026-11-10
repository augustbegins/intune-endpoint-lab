## Lab 2: Groups

Goal: Create groups that target devices and users automatically, so policies can be assigned at scale.

What I built

Lab-Devices-Windows: dynamic device group with the rule (device.deviceOSType -eq "Windows")
Lab-Users-Pilot: static user group containing my second test user

Steps

Intune admin center > Groups > New group.
Created the dynamic device group and added the membership rule above.
Created the static user group and added the test user.
Waited for dynamic membership to process and confirmed the VM appeared in the device group.

Result:

Takeaway: Dynamic groups remove manual assignment work, but membership isn't instant. Allow a few minutes before troubleshooting why a device isn't getting a policy.
