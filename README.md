# ms_activate
activate ms office 2016 and newer


Run this Code on CMD with Admin previllage

```
cd /d %ProgramFiles%\Microsoft Office\Office16
cd /d %ProgramFiles(x86)%\Microsoft Office\Office16
for /f %x in ('dir /b ..\root\Licenses16\ProPlus2019VL*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"
cscript ospp.vbs /setprt:1688
cscript ospp.vbs /unpkey:6MWKP >nul
cscript ospp.vbs /inpkey:NMMKJ-6RK4F-KMJVX-8D9MJ-6MWKP
cscript ospp.vbs /sethst:104.244.78.23
cscript ospp.vbs /act
```

IF SUCCESSFULL, THIS WILL SHOW UP (at the end):
![image](https://user-images.githubusercontent.com/34002411/162635362-18de5ea9-15d1-4b4d-acf5-420b61bf4076.png)


IF NOT, try again and again. (proxy links will be provided soon)

and you are all done.
