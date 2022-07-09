**Sublime** \
https://www.sublimetext.com/download_thanks?target=win-x64

**Oh My Posh** \
https://ohmyposh.dev/docs/installation/windows
```
Install-Module -Name Terminal-Icons -Repository PSGallery
New-Item -Path $PROFILE -Type File -Force
notepad $PROFILE
oh-my-posh init pwsh | Invoke-Expression
Import-Module -Name Terminal-Icons
. $PROFILE
```
- https://www.nerdfonts.com/font-downloads > Caskaydia Cove Nerd Font
- Windows Terminal > Settings > <Terminal> > Appearance

**WSL2** \
Register for Windows Insider Programme \
Download update https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi

**Docker Desktop** \
https://www.docker.com/products/docker-desktop/

**dotnet** \
https://dotnet.microsoft.com/en-us/download

**7zip** \ 
https://www.7-zip.org/

**kubectl** \
https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/

**k9s** \
https://github.com/derailed/k9s/releases

**az cli** \
$ProgressPreference = 'SilentlyContinue'; Invoke-WebRequest -Uri https://aka.ms/installazurecliwindows -OutFile .\AzureCLI.msi; Start-Process msiexec.exe -Wait -ArgumentList '/I AzureCLI.msi /quiet'; rm .\AzureCLI.msi

**VSCode** \
https://code.visualstudio.com/docs/?dv=win