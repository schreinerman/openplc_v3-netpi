# openplc_v3-netpi
a patch to make OpenPLC V3 usable with Hilscher NetPI

copy and apply the netpi.patch file in the root folder of OpenPLC_v3
```
patch -s -p0 < netpi.patch 
```

Copy the file hardware_layers/netpi.cpp to `webserver/core/hardware_layers`

Execute `./install.sh rpi`
