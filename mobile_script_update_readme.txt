open command prompt as Administrator Mode

execute  below command

cd <python_installed_path_example_given_below>

(Example  cd C:\TataElxsi\FalconEye\FEPython37\Lib\site-packages )

(NOTE: check the path from your system and give)

 now run below command to unregister dll
 
 C:\Windows\Microsoft.NET\Framework\v4.0.30319\RegAsm.exe /u MobileScriptingLibrary.dll

 Now copy and replace MobileScriptingLibrary.dll in the path  <python_installed_path_example_given_below>
Example "C:\TataElxsi\FalconEye\FEPython37\Lib\site-packages"
 
 now run the below command in same command prompt opened earlier, to register new dll
 
 C:\Windows\Microsoft.NET\Framework\v4.0.30319\RegAsm.exe MobileScriptingLibrary.dll /tlb:MobileScriptingLibrary.tlb /codebase


Carryout same steps for Python27 as well.(this path will be inside c:/Program Files(86)/Python 2.7/Lib/Site_packages)


command unreg -- delete -- replace new -- reg command

c/initoub/Python 37/lib/sitepackages/

UNREG CMD:    C:\Windows\Microsoft.NET\Framework\v4.0.30319\RegAsm.exe /u MobileScriptingLibrary.dll

REG CMD:   C:\Windows\Microsoft.NET\Framework\v4.0.30319\RegAsm.exe MobileScriptingLibrary.dll /tlb:MobileScriptingLibrary.tlb /codebase

****************************************** 

C:\Windows\Microsoft.NET\Framework\v4.0.30319\RegAsm.exe /u ScriptingLibrary.dll

C:\Windows\Microsoft.NET\Framework\v4.0.30319\RegAsm.exe ScriptingLibrary.dll /tlb:ScriptingLibrary.tlb /codebase


*************************** any service .exe uninstall and uninstall  **********

cd C:\inetpub\wwwroot\FalconEye\WebServices\P_Node\ExecutionService\bin\Release

C:\Windows\Microsoft.NET\Framework\v4.0.30319\installutil /u ExecutionService.exe

C:\Windows\Microsoft.NET\Framework\v4.0.30319\installutil ExecutionService.exe