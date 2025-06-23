# xui-one-install-guide

Step-by-step guide for installing XUI.ONE 1.5.13 on Ubuntu 20.04

# XUI.ONE 1.5.13 Install Guide

![View Full Guide](https://img.shields.io/badge/View%20Full%20Guide-iptvtools.io-blue?style=for-the-badge\&logo=readme)

Installing XUI.ONE 1.5.13 from scratch is simple if you follow this complete step-by-step tutorial. This guide assumes you have access to a dedicated server running Ubuntu 20.04.

---

## 💻 Recommended Server Specifications

To ensure a smooth IPTV experience with XUI.ONE, your server should meet these minimum specs:

* **CPU:** Intel Xeon or AMD Ryzen (6+ cores)
* **RAM:** 16–32 GB DDR4
* **Storage:** SSD or NVMe (480 GB or more)
* **Network:** Dedicated 1 Gbps port
* **Operating System:** Ubuntu 20.04 LTS (clean install)

---

## 🌐 Recommended Providers

We recommend choosing reliable and affordable providers such as:

* **Hetzner** – Affordable dedicated servers, scalable and reliable infrastructure.
* **Worldstream** – Great network performance, good pricing, and fast provisioning.

These providers offer excellent balance between price, performance, and flexibility, especially for IPTV services.

---

## 🔧 Step 1: Get Root Access

Once your server is installed with Ubuntu 20.04, open your terminal and run:

```bash
sudo su -
```

Enter your server password when prompted. If successful, you will notice the terminal prompt change to `#`, indicating root access.

---

## 📦 Step 2: Download and Install XUI.ONE

To download the full installation package and instructions, please visit the official documentation page:

🔗 [XUI.ONE 1.5.13 Installation Guide on IPTVTools.io](https://iptvtools.io/xuidocs/xui-one-1-5-13-install-guide/)

This page contains the latest download links, full setup instructions, and any necessary updates or patches.

---

## ⚙️ Step 3: Configuration Prompt

During installation, you will be asked:

```
Overwrite sysctl configuration? Recommended! (Y / N):
```

Type `y` and press Enter.

Installation will continue and finalize the setup including your license.

---

## 🔐 Final Step: Panel Access Info

After a few moments, the script will output the following:

* ✅ Access URL to your XUI.ONE panel
* 🔑 Secret connection code
* 🗂️ MySQL credentials saved at: `/root/credentials.txt`

Make sure to save this information securely, as it will be required to log into your panel.

---

## 🚀 What’s Next: Setup and Configuration

Once your panel is installed, log in using the URL and credentials provided. You can now:

* Add your IPTV streams and channels
* Configure load balancers
* Set up EPG sources
* Add users and resellers
* Secure the panel using the built-in key regeneration tool

---

🔗 For full documentation and other IPTV tools, visit [iptvtools.io](https://iptvtools.io)
