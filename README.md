# Invoke-Mimikatz-Bypass
This script dynamically decodes and executes a Base64 encoded Mimikatz script, allowing users to bypass security measures and run specified Mimikatz commands.

## Usage
.\Invoke-Mimikatz-Bypass.ps1 -mimikatzCommands "privilege::debug", "sekurlsa::logonpasswords", "sekurlsa::tickets"

## Disclaimer
This script is intended for educational purposes only. The use of this script in unauthorized environments is illegal and unethical. The authors are not responsible for any misuse or damage caused by this script.

## Acknowledgments
This script incorporates parts of the Invoke-Mimikatz.ps1 script from the Nishang repository by SamratAshok. 

## PoC
![](https://github.com/okankurtuluss/Invoke-Mimikatz-Bypass/blob/okankurtuluss/main/ScreenShots/system%20information.png)

![](https://github.com/okankurtuluss/Invoke-Mimikatz-Bypass/blob/okankurtuluss/main/ScreenShots/Windows%20Defender.png)

![](https://github.com/okankurtuluss/Invoke-Mimikatz-Bypass/blob/okankurtuluss/main/ScreenShots/Antivirus-Scanning-1.png)

![](https://github.com/okankurtuluss/Invoke-Mimikatz-Bypass/blob/okankurtuluss/main/ScreenShots/Antivirus-Scanning-2.png)

![](https://github.com/okankurtuluss/Invoke-Mimikatz-Bypass/blob/okankurtuluss/main/ScreenShots/Antivirus-Scanning-3.png)

![](https://github.com/okankurtuluss/Invoke-Mimikatz-Bypass/blob/okankurtuluss/main/ScreenShots/PoC-1.png)

![](https://github.com/okankurtuluss/Invoke-Mimikatz-Bypass/blob/okankurtuluss/main/ScreenShots/PoC-2.png)
