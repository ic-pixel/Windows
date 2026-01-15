

USER MANAGEMENT

==============================



Create a new local user:


net user **username** password /add



Example:

net user **john** 1234 /add





Delete a user:

net user **username** /delete



Example:

net user **john** /delete





List all users on the system:

net user





PASSWORD MANAGEMENT

==============================



Change a user's password:

net user **username** new\_password



Example:

net user **mary** 4321





Force password change at next login:

net user **username** /logonpasswordchg:yes





LOCAL GROUPS

==============================



Add a user to the Administrators group:

net localgroup Administrators username /add



Example:

net localgroup Administrators john /add





Remove a user from the Administrators group:

net localgroup Administrators username /delete





List members of the Administrators group:

net localgroup Administrators





SYSTEM INFORMATION

==============================



Display system information:

systeminfo



Display computer name:

hostname



Display Windows version:

ver



NETWORK

==============================



Show network configuration:

ipconfig



Show detailed network configuration:

ipconfig /all



Release IP address:

ipconfig /release



Renew IP address:

ipconfig /renew





USEFUL TOOLS

==============================



Open Local Group Policy Editor:

gpedit.msc



Open Local Users and Groups:

lusrmgr.msc



Open Device Manager:

devmgmt.msc



Open Disk Management:

diskmgmt.msc


----------------------------------

WARNING

Some actions are irreversible.



