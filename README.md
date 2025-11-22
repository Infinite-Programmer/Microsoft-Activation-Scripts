# Microsoft Activation Scripts (MAS)

<p align="center"><img src="https://massgrave.dev/img/logo_small.png" alt="MAS Logo"></p>

<h1 align="center">Microsoft Activation Scripts (MAS)</h1>

<p align="center">An open-source, reliable, and feature-rich activator for Windows and Office. Supports HWID, Ohook, TSforge, KMS38, and Online KMS activation with advanced troubleshooting features.</p>

<hr/>

## 🚀 Overview

Microsoft Activation Scripts (MAS) is a collection of powerful scripts designed to activate:

* **Windows (Vista → Latest Windows 11)**
* **Microsoft Office (2010 → Latest)**
* **Windows Extended Security Updates (ESU)**
  All using safe, open-source, and well-documented methods.

---

## 🛠️ How to Activate Windows / Office / ESU

Below are two easy methods. If one fails due to network or DNS blockage, the alternate method will work.

---

## 🔹 Method 1 — PowerShell (Recommended)

1. **Open PowerShell**
   Click the **Start Menu**, search for `PowerShell`, and launch it.

2. **Copy and Paste the Command** for your version:

### ✔️ For Windows 8 / 10 / 11

```powershell
irm https://get.activated.win | iex
```

If the above fails (blocked by DNS/ISP), try this alternate (requires updated Win10/11):

```powershell
iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
```

### ✔️ For Windows 7 and later

```powershell
iex ((New-Object Net.WebClient).DownloadString('https://get.activated.win'))
```

3. The script menu will appear. **Follow the highlighted green options** to activate Windows or Office.

4. **Done! 🎉**

---

## 🔹 Method 2 — Traditional Script (Vista and Later)

1. Download the script package:

   * **Direct Script:** [MAS_AIO.cmd](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?path=/MAS/All-In-One-Version-KL/MAS_AIO.cmd&download=true)
   * **Full ZIP:** [Download ZIP](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?$format=zip)

2. Run the file named **`MAS_AIO.cmd`**.

3. Choose the activation option you need.

4. That’s it — activation complete.

---

## 💡 Tips & Notes

* Some ISPs/DNS providers block MAS domains. Enable **DNS-over-HTTPS (DoH)** to bypass blocks. Learn more [here](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/).
* Troubleshooting issues? Visit the official **[Help Page](https://massgrave.dev/troubleshoot)**.
* Need support? Create an issue on **[GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts/issues)**.

---

## 📦 Additional Tools

MAS also supports activation for:

* **Office for macOS**
* **Visual Studio**
* **Windows XP**
* **RDS CALs**

Learn more: [https://massgrave.dev/unsupported_products_activation](https://massgrave.dev/unsupported_products_activation)

If you want to automate MAS silently, see: [https://massgrave.dev/command_line_switches](https://massgrave.dev/command_line_switches)

---

## 🔍 Security Notice

* `IRM` downloads a script, `IEX` executes it.
* Always ensure the URL is exactly: **[https://get.activated.win](https://get.activated.win)**
* Beware of imitations; some websites spread malware by changing URLs.

---

## 📅 Latest Release

```
Version: 3.7
Release Date: 11-Sep-2025
```

---

## 🔗 Useful Links

* **Troubleshooting / Help:** [https://massgrave.dev/troubleshoot](https://massgrave.dev/troubleshoot)
* **Download Genuine Windows & Office ISOs:** [https://massgrave.dev/genuine-installation-media](https://massgrave.dev/genuine-installation-media)
* **Homepage:** [https://massgrave.dev/](https://massgrave.dev/)

---

## 🌐 Community & Repositories

<div align="center">

[![GitHub](https://massgrave.dev/img/logo_github.png)](https://github.com/massgravel/Microsoft-Activation-Scripts)
[![AzureDevOps](https://massgrave.dev/img/logo_azuredevops.png)](https://dev.azure.com/massgrave/_git/Microsoft-Activation-Scripts)
[![Gitea](https://massgrave.dev/img/logo_gitea.png)](https://git.activated.win/massgrave/Microsoft-Activation-Scripts)

</div>

<div align="center">

[![Discord](https://massgrave.dev/img/logo_discord.png)](https://discord.gg/j2yFsV5ZVC)
[![Reddit](https://massgrave.dev/img/logo_reddit.png)](https://www.reddit.com/r/MAS_Activator)
[![Bluesky](https://massgrave.dev/img/logo_bluesky.png)](https://bsky.app/profile/massgrave.dev)
[![Twitter](https://massgrave.dev/img/logo_x.png)](https://twitter.com/massgravel)

</div>

---

<p align="center">Made with ❤️ for the community</p>
