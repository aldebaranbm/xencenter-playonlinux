# xencenter-playonlinux
**XenCenter** / XCP-ng Center - PlayOnLinux Vault (Wine i386)

# How to install (3 steps)
1. Install **wine** (https://wiki.winehq.org/Download) and **playonlinux** (https://www.playonlinux.com/en/download.html)
2. In **PlayOnLinux** use the option **Plugins** -> **PlayOnLinux Vault** to install/restore the **xencenter.polApp** file (https://github.com/aldebaranbm/xencenter-playonlinux/releases/latest)
3. **Connect** in your XenServer/XCP-ng with **port 80**, example: *192.168.0.100:80*
> *XCP-ng Center is "same" of XenCenter, you can use it to connect in your Citrix XenServer.*

### Need update?
You can update manually installing new version of XenCenter/XCP-ng Center inside of lastest release <s>or patience to wait one new realease in this repository</s>.
## Alert! Security risk
* You need connect in servers with ***port 80***, the default port not work. Caution for use out of our local network!
### How to re-build
<s>If you not trust me or </s>**Need re-make this work?** ***Go a head!***
1. Install **wine** (https://wiki.winehq.org/Download)
2. Install **playonlinux** (https://www.playonlinux.com/en/download.html)
3. Make the **prefix**
4. Install dependencies in prefix **Internet Explorer 8**; **.NET Framework 2.0 SP2**; **.NET Framework 4.7.2**
5. Install **XenCenter/XCP-ng Center**
> *Install IE8 and .NET 2.0 in winXP version. To .NET 4.7.2 use win7 version.*
### Not work?
> <s>oh, damn!</s> Sorry, but, i using **Debian 9.7 (amd64)** with **Wine 4.0 (i386)**, this run with good stability for me home server/personal use. I use the package playonlinux of debian official contrib repository and wine package is from official wine stable repository.
