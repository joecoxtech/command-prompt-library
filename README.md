# Windows Commands Everyone Should Know (By JoeCoxTech)

From my TikTok series 👇  

Video 1: https://www.tiktok.com/@joecoxtech/video/7568573474717863181  
Video 2: https://www.tiktok.com/@joecoxtech/video/7569281508821716238

| Command | Description | Video |
|---------|-------------| ----- |
| winget upgrade --all | Updates all apps on your system, replacing chocolatey or manual updating | Video 1 |
| sfc /scannow | Repairs corrupt system files | Video 1 |
| DISM /Online /Cleanup-Image /Restore Health | Deep repair tools | Video 1 |
| powercfg /batteryreport | Creates battery health report | Video 1 |
| ipconfig /displaydns | Shows DNS cache | Video 1 |
| netstate -ano | Shows ports + process IDs | Video 1 |
| tasklist /svc | Shows what services and processes are running | Video 1 |
| shutdown /s /t 0 | Force shutdown immediately (works remotely) | Video 1 |
| shutdown /i | Graphical remote shutdown manager (IT Gold) | Video 1 |
| getmac | Shows MAC address of local + remote machines | Video 1 |
| wmic product get name | Lists installed apps | Video 1 |
| gpupdate /force | Force Group Police update | Video 1 |
| net use \\computer\C$ | Access someone's C drive silently (with creds) | Video 1 |
| whoami /groups | Shows AD groups you're in | Video 1 |
| choco install <package> | Show Chocolately for software installs | Video 1 |
| taskkill /f /im explorer.exe & start explorer.exe | Restart Windows Explorer | Video 1 |
| gpresult /r | Shows every Group Policy applied to user and computer | Video 2 |
| netsh wlan show profiles | Shows all WiFi networks previous joined | Video 2 |
| netsh wlan show profiles name="YourWifi" key=clear | Shows specific wifi network password in the clear | Video 2 |
| chkdsk /f | Checks and repairs file system errors | Video 2 |
| wmic diskdrive get status | Health check on hard drives or SSDs | Video 2 |
| tasklist /fi "imagename eq chrome.exe " | Shows how much resource an application is consuming | Video 2 |
| net use \\ComputerName\C$ /user:DOMAIN\AdminUser | Access another computer's C Drive on the network | Video 2
| systeminfo | System audit- Windows version, build number, install date, BIOS version, etc. | Video 2 |
