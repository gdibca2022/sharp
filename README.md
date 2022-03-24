# sharp releases
Sharp tings for cutting through networks. Most binaries have some sort of obfuscation. Recommend loading them via netloader (named loadyload.exe on this repo).

## Binaries:

- SharpImpersonation.exe - token impersonation in C#
- betterBelt.exe - SeatBelt but obfuscated
- doggo.ps1 - Bloodhound injestor
- loadyload.exe - netloader to load C# binaries via the web or local paths. Web better as don't need to obfuscate target exe.
- msinfo32.exe - cobalt strike beacon. DONT RUN THIS unless you want RT to go through your stuff :)
- toknock.ps1 - Invoke-TokenManipulation but obfuscated. Usage below
```
Import-Module .\toknock.ps1
pedagogic -Enumerate
pedagogic -Username "DOMAIN\victim_user" -CreateProcess cmd.exe
```

Enjoy.


