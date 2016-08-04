# winrm-connect
Early alpha! Pleade be careful!
Connects via Kerberos to target server.

CMD/Powershell remote connector for Linux

Usage: winrm-connect SERVER [SCRIPT [ARG]]<br />
When connected type ps/powershell to switch to powershell context.<br />
When in powershell context type exit to switch back to cmd.<br />

The initial goal is to have a wrapper to easily connect to Windows machines. Uses pywinrm.

<h2>Prequisites</h2>
You will need a working kerberos configuration (tested with machines joined with realmd) and a valid Kerberos ticket (klist).<br />
You will also need a winrm activated windows machine.
Packages:
* pywinrm
* requests-kerberos

<h2>Status</h2>
* Context between commands is not saved
 
<h3>ToDos</h3>
* autocomplete
* Directory switching
