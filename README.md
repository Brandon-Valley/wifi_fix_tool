# wifi_fix_tool
Quick script to disable then re-enable wifi device driver (win 10)


https://stackoverflow.com/questions/20575257/how-do-i-run-a-powershell-script-when-the-computer-starts


## Setup

---

- Set `$adapterName` in `wifi_fix.ps1` with the name of your wireless network adapter. You can find the adapter name by running `Get-NetAdapter` in a PowerShell window and looking for the name of your wireless adapter.
- Add a windows shortcut to your windows startup folder to run `hotkey_run_wifi_fix_tool.ahk` on startup.
    - Example path: `C:\Users\Brandon\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`
- Run this new shortcut manually (by double clicking it) to run it for the first time
- Run with `Ctrl Shift w`