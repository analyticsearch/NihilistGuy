# NihilistGuy
A simple tool to dump lsass memory space with the ability to unhook NTDLL.dll 

It will dump the lsass.exe as WindowsUpdateProvider.pod and store it at C:\windows\Temp
The purpose of this strategy is to bypass security controls that rely on monitoring the creation of dmp files.
