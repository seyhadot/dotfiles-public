
## Install 
    iwr -useb get.scoop.sh | iex
#   
    scoop install curl sudo jq neovim gcc nvm fzf
#     
    Install-Module posh-git -Scope CurrentUser -Force
# 
    Install-Module oh-my-posh -Scope CurrentUser -Force
# 
    nvim .\.config\powershell\user_profile.ps1
# 
    nvim $PROFILE.CurrentUserCurrentHost
    #Paste This Code
    . $env:USERPROFILE\.config\powershell\user_profile.ps1
# 
    Install-Module -Name Terminal-Icons -Repository PSGallery -Force                                                                              
    Install-Module Terminal-Icons
    Install-Module -Name z -Force
    Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck

    Set-PSReadLineOption -PredictionSource History
    Set-PSReadLineOption -PredictionViewStyle ListView

    Install-Module -Name PSFzf -Scope CurrentUser -Force
