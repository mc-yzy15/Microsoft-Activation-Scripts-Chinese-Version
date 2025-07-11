[![Sync MAS Fork with Upstream](https://github.com/mc-yzy15/Microsoft-Activation-Scripts/actions/workflows/syncfork.yml/badge.svg)](https://github.com/mc-yzy15/Microsoft-Activation-Scripts/actions/workflows/syncfork.yml)

# Microsoft-Activation-Scripts-Chinese-Version
开源版 Windows 和 Office 激活工具，具备硬件识别码（HWID）、Ohook、TSforge、KMS38 和在线 KMS 激活功能，同时还包含高级故障排除功能。

<p align="center"><img src="https://massgrave.dev/img/logo_small.png" alt="MAS Logo"></p>

## Download / How to use it?

### Method 1 - PowerShell (Windows 8 and later) ❤️

1.   Open PowerShell (Not CMD). To do that, right-click on the Windows start menu and select PowerShell or Terminal.
2.   Copy and paste the code below and press enter  
```
irm https://mc-yzy15.github.io/MAS-Bootstrap | iex
```
3.   You will see the activation options. Choose (1) HWID for Windows activation. Choose (2) Ohook for Office activation.
4.   That's all.

---

### Method 2 - Traditional (Windows 7 and later)

<details>
  <summary>Click here for info</summary>

1.   Download the file using the links provided below.  
`https://github.com/mc-yzy15/Microsoft-Activation-Scripts/archive/refs/heads/master.zip`  
or  
`https://github.com/mc-yzy15/Microsoft-Activation-Scripts/archive/master.zip`
2.   Right-click on the downloaded zip file and extract
3.   In the extracted folder, find the folder named `All-In-One-Version`
4.   Run the file named `MAS_AIO.cmd`
5.   You will see the activation options, follow the on-screen instructions.
6.   That's all.

</details>

---

### Not working ❓

- If you are **unable to launch MAS** using the PowerShell method, please refer to **Method 2** listed above.
- If MAS is launched and the script shows any errors, check for any troubleshooting steps mentioned in blue color and try to follow those.
- If you have any issues, please feel free to reach out to us [here](https://massgrave.dev/troubleshoot).

---

> [!NOTE]
>
> - The IRM command in PowerShell downloads a script from a specified URL, and the IEX command executes it.
> - Always double-check the URL before executing the command and verify the source if manually downloading files.
> - Be cautious, as some spread malware disguised as MAS by using different URLs in the IRM command.

---

<p align="center">Made with Love ❤️ by massgrave.dev and their Community </p>
<p align="center">Tweaked with Passion 🔥 by Dolfie </p>
