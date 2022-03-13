# Dot-NEt

If you've got a Windows 10 installation USB, plug it in and let's assume it's the E drive

Go to "E:\sources\sxs", a file in this location with name: "microsoft-windows-netfx3-ondemand-package.cab". It should be around 70mb in size

Copy and paste it into "C:\Windows", rename it as: NetFx3.cab

Run Command prompt as Administrator:

Start

Type "Command Prompt"

Click "Run as administrator"

Type the following command: dism /online /Enable-Feature /FeatureName:NetFx3 /Source:"%windir%" /LimitAccess

Press Enter and waiting for the installation finish (100%)

Reboot



https://tb.rg-adguard.net/public.php
