# nodejs-portable-windows-powershell
```
$WebClient=New-Object Net.WebClient
$Uri='https://nodejs.org/dist/v20.9.0/node-v20.9.0-win-x64.zip'
$WebClient.DownloadFile($Uri, "node.zip")
Expand-Archive -Path node.zip
```
