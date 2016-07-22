# winrm-connect
CMD/Powershell remote connector for Linux

Usage: winrm-connect SERVERNAME<br />
When connected type ps/powershell to switch to powershell context.<br />
When in powershell context type exit to switch back to cmd.<br />

The initial goal is to have a wrapper to easily connect to Windows machines. Uses pywinrm.

<h2>Prequisites</h2>
You will need a working kerberos configuration (tested with machines joined with realmd) and a valid Kerberos ticket (klist)
* pywinrm
* requests-kerberos
