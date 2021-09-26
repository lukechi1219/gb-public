# Chocolatey + nodejs

* Installing Chocolatey
  * 用系統管理員執行 Windows PowerShell
  * 按照安裝說明, 在 PowerShell 執行一句 script: [https://chocolatey.org/install](https://chocolatey.org/install)

```text
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

* 執行 choco 確認安裝成功
  * 顯示 Chocolatey v0.10.15

```text
C:\Users\luke.chi>choco
Chocolatey v0.10.15
Please run 'choco -?' or 'choco <command> -?' for help menu.
```

* 安裝 nodejs-lts

```text
choco install nodejs-lts
```

* 執行 choco list -l 確認安裝成功
  * 顯示 nodejs-lts 14.16.0

```text
C:\Users\luke.chi>choco list -l
nodejs-lts 14.16.0
```

* 執行 node --version
  * v14.16.0

```text
C:\Users\luke.chi>node --version
v14.16.0
```

* 執行 npm --version
  * 7.6.3
  * 如果版本比較低, 可以用下面指令升級
    * npm install -g npm

```text
C:\Users\luke.chi>npm --version
7.6.3
```

.

