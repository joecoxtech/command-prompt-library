# Windows Commands Everyone Should Know (By JoeCoxTech)

From my TikTok series 👇  

Video 1: https://www.tiktok.com/@joecoxtech/video/7568573474717863181  
Video 2: https://www.tiktok.com/@joecoxtech/video/7569281508821716238

| Command | Description |
|---------|-------------|
| winget upgrade --all | Updates all apps on your system, replacing chocolatey or manual updating |
| sfc /scannow | Repairs corrupt system files |
| DISM /Online /Cleanup-Image /Restore Health | Deep repair tools |
| powercfg /batteryreport | Creates battery health report
| ipconfig /displaydns | Shows DNS cache |
| netstate -ano | Shows ports + process IDs |
| tasklist /svc | Shows what services and processes are running |
| shutdown /s /t 0 | Force shutdown immediately (works remotely) |
| shutdown /i | Graphical remote shutdown manager (IT Gold) |
| getmac | Shows MAC address of local + remote machines |
| wmic product get name | Lists installed apps |
| gpupdate /force | Force Group Police update |
| net use \\computer\C$ | Access someone's C drive silently (with creds) |
| whoami /groups | Shows AD groups you're in |
| choco install <package> | Show Chocolately for software installs
| taskkill /f /im explorer.exe & start explorer.exe | Restart Windows Explorer |
