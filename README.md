# Invoke-Mimikatz-Bypass
This script dynamically decodes and executes a Base64 encoded Mimikatz script, allowing users to bypass security measures and run specified Mimikatz commands.

# Usage
.\Invoke-Mimikatz-Bypass.ps1 -mimikatzCommands "privilege::debug", "sekurlsa::logonpasswords", "sekurlsa::tickets"

# Disclaimer
This script is intended for educational purposes only. The use of this script in unauthorized environments is illegal and unethical. The authors are not responsible for any misuse or damage caused by this script.

# Acknowledgments
This script incorporates parts of the Invoke-Mimikatz.ps1 script from the Nishang repository by SamratAshok. 

# PoC
