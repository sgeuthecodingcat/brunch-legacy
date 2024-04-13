<div style='text-align: center;'>
  Brunch Legacy 
</div>

# About this project
First of all, thank user SebanC for the original brunch repository.

This project allows for booting ChromeOS on non-ChromeOS devices that Brunch does not support

# Supported Devices

✔️ Supported Hardware:

- Intel I series CPUs from 2nd gen or above
- AMD Ryzen

❌ Unsupported Hardware:

- Intel I series CPUs from 1st gen are not supported.
- dGPUs are not supported.
- Virtual Machines are not supported.
- ARM CPUs are not supported.


# What recovery image do I use?

Use [Volteer](https://cros.tech/device/volta/) for AMD.
Use [Rammus](https://cros.tech/device/shyvana/) for Intel.

Install:
```sudo bash chromeos_install.sh -src <recovery image> -dst /dev/disk```
Replace /dev/disk with the device you want to install it on (eg /dev/sda, /dev/mmcblk0)

Your install disk will NEVER be a swap drive or a loop drive!
