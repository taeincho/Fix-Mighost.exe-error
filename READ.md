<h1>Copyright 2023. Taein all rights reserved.</h1>
<h1>1. Install DISM</h1>
Launch this command:
DISM.exe /Online /Cleanup-Image /RestoreHealth /Source:C:\RepairSource\Windows /LimitAccess
<h1>2. Launch DISM SFC</h1>
launch this command:
sfc /scannow
