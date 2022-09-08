
## Download Nerd Fonts
https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/JetBrainsMono.zip

https://github.com/git-for-windows/git/releases/download/v2.35.1.windows.2/Git-2.35.1.2-32-bit.exe

https://go.dev/learn/

## Install Cancel changes
    Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
    irm https://deno.land/install.ps1 | iex
    Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
    iwr -useb get.scoop.sh | iex
    scoop install curl sudo jq neovim gcc nvm fzf make
    nvm install 16.17.0
    nvm use 16.17.0
    Install-Module posh-git -Scope CurrentUser -Force
    #Install-Module oh-my-posh -Scope CurrentUser -Force
    winget install JanDeDobbeleer.OhMyPosh -s winget
    Set-ExecutionPolicy Bypass -Scope Process -Force; Invoke-Expression ((New-Object System.Net.WebClient).DownloadString('https://ohmyposh.dev/install.ps1'))
    Install-Module -Name Terminal-Icons -Repository PSGallery -Force                                                                                       
    Install-Module Terminal-Icons
    Install-Module -Name z -Force
    Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck
    Set-PSReadLineOption -PredictionSource History
    Set-PSReadLineOption -PredictionViewStyle ListView
    Install-Module -Name PSFzf -Scope CurrentUser -Force
### Open Vim or Editor 
    nvim $PROFILE.CurrentUserCurrentHost
### Paste Into Vim 
    . $env:USERPROFILE\.config\powershell\user_profile.ps1
 
