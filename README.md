# VNC Thumbnail Viewer
Automatically exported from code.google.com/p/vncthumbnailviewer

This repository houses my downloaded and modified version of VNC Thumbnail Viewer
You can find more information about the original creator and the project here:
https://thetechnologyteacher.wordpress.com/vncthumbnailviewer

## Load List Of Hosts
It is important to know that the list of hosts file needs to be created in this format. 
After loading in a list of hosts created in the following way you can then save the list of hosts with encryption enabled.
This was easier for me than adding the hosts one by one and then saving the result.

```xml
<?xml version="1.0" standalone="yes"?>
<Manifest Encrypted="0" Version="1.4">
    <Connection Host="10.0.0.1" Port="5900" SecType="2" Password="password"/>

</Manifest>
```
