<h2> Open Powershell as Administrator and run this code </h2>

```powershell
wsl --install
```

<h2> Use this if not work </h2>

```powershell
# 1
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
# 2
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
# 3
wsl --set-default-version 2
```

