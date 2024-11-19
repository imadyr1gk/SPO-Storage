# Instructions d'installation et de connexion

Avant d'exécuter le script `SPO-Storage.ps1`, vous devez :

1. **Installer le module PnP.PowerShell** en utilisant la commande suivante :
    ```powershell
    Install-Module Microsoft.Online.SharePoint.PowerShell 
    ```

2. **Importer le module** avec la commande :
    ```powershell
   Import-Module Microsoft.Online.SharePoint.PowerShell -ErrorAction Stop
    ```

3. **Se connecter au site en remplaçant tenant par le nom de votre tenant :
    ```powershell
   Connect-SPOService -Url https://tenant-admin.sharepoint.com
    ```
