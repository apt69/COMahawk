# COMahawk
Weaponizing CVE-2019-1405 and CVE-2019-1322

## Video Demo
https://vimeo.com/373051209

## Usage

### Compile or Download from Release

1. Run COMahawk.exe
2. ???
3. Hopefully profit

or

1. COMahawk.exe <custom command to run> (ie. COMahawk.exe "net user /add test123 lol123 &")
2. ???
3. Hopefully profit

## Concerns
I noticed that on my W10 1709, the second bug does not exist aka Local Service does not have permission to modify/execute/stop UsoSvc

However, it is confirmed that my 1903 does indeed have this bug so maybe it was introduced somewhere inbetween.

Also, since you are executing from a service - you most likely cannot spawn any Window hence all command will be "GUI-less". Maybe different session? Idk, it is too late and I am tired haha.

## Credits:
https://twitter.com/leoloobeek for helping me even when he doesn't have a laptop

https://twitter.com/TomahawkApt69 for being the mental support and motivation

and most of all:

https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2019/november/cve-2019-1405-and-cve-2019-1322-elevation-to-system-via-the-upnp-device-host-service-and-the-update-orchestrator-service/

for discovering and publishing the write up. 100% of the credit goes here.
