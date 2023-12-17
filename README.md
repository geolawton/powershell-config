# powershell-config
Powershell config based on Scott Hanselman's walkthrough

## Find the walkthrough where I based my profile on [here](https://www.hanselman.com/blog/my-ultimate-powershell-prompt-with-oh-my-posh-and-the-windows-terminal)

[Link to font](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/CascadiaCode.zip?WT.mc_id=-blog-scottha)

### Instructions
- Download the Terminal app and Powershell from the Microsoft Store
  - [Powershell](https://www.microsoft.com/store/productId/9MZ1SNWT0N5D?ocid=pdpshare)
  - [Terminal](https://www.microsoft.com/store/productId/9N0DX20HK701?ocid=pdpshare)
![image](https://github.com/geolawton/powershell-config/assets/90012201/a1ae4eea-7b85-448e-9cfa-7af346fe89da)
![image](https://github.com/geolawton/powershell-config/assets/90012201/4316e5c1-fb83-4ebc-81e4-18b647381065)
  
- [Download](https://ohmyposh.dev/) oh my posh
- Run the following commands in powershell
```powershell
Install-Module -Name Terminal-Icons -Repository PSGallery
Install-Module PSReadLine -AllowPrerelease -Force
```
- In powershell run `code $PROFILE` and paste the contents of `./profile`
- Restart Powershell. Enjoy
![image](https://github.com/geolawton/powershell-config/assets/90012201/e121f96c-1282-468e-8f5e-a72c69882d2b)
