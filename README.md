# script

## Azure

### 创建开机API
登录azure.com,找到顶部azure cloudshell powershell运行一下代码：
```powershell
iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/hxwuhxj/script/raw/main/credential.ps1'))
```

### 创建永久API密钥
```bash
az ad app credential reset --id CLIENT_ID --display-name NAME --end-date 2999-12-31
```
