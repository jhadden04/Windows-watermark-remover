# Windows-watermark-remover
# Python 3
```
import os
print('run "Activation.bat" file as admin, then press enter to restart')
os.startfile('"D:\\user\\Documents"')
input()
os.system("shutdown /r /t 1")
print('shutdown')
```
for the file that is opened you need to open notepad and copy this code:
```
@echo off
taskkill /F /IM explorer.exe
explorer.exe
exit
```
then you save this as Activation.bat, and change the path in the code to where you have saved it
