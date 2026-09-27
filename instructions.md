
## Steps for setting up global streaming using any gaming device, a Windows desktop computer, and NordVPN

1. Connect desktop to the internet
     - (preferably Wi‑Fi, so the Ethernet port stays free for the Xbox).
2. Connect LAN cable: PC Ethernet port to Xbox.
3. Open NordVPN on desktop.
     - In Settings, set the protocol to OpenVPN UDP or OpenVPN TCP (not NordLynx).
     - Then connect to a server.
4. Right‑click the network icon on desktop
    - Go to Network and Internet settings
    - Then to Advanced network settings
    - Then More network adapter options.
       - You should see at least:
       - your Wi‑Fi
       - Ethernet (the Xbox cable)
       - a NordVPN adapter (OpenVPN Data Channel Offload for NordVPN or TAP-NordVPN)
5. Right‑click the NordVPN adapter (OpenVPN Data Channel Offload for VPN) in the Network Connections window on desktop
    - Then go to Properties, Sharing tab.
    - Check Allow other network users to connect through this computer’s Internet connection.
    - Under Home networking connection choose:
       - Ethernet (or the adapter of your choice from desktop to device)
    - Click OK.</br>
     *Note, you should not share from WIFI, NordLynx(if using NordVPN), or vEthernet. Only share from the OpenVPN adapter to Ethernet.*
6. On the desktop:
     - Leave the PC on and running
     - Change any settings to keep awake and no sleep/timeout
     - Make sure the VPN you are using remains connected to the region that you are viewing content from.
7. On the gaming device (this example uses Xbox):
     - Go to Settings, Network, Network Settings
     - It should show the wired connection on your device
     - Run Test Network Connection </br>
     - If no connection on first attempt:
        - Unplug/replug the cable, disable then re-enable sharing on the VPN adapter, and test for connection again. NAT type sometimes is finicky and needs to be refreshed after being fully set up.
     - If no connection on second attempt:
        - if you are having trouble getting device to stay on wired connection at this stage. On device go to network history and forget current wifi network. This forces the device to the wired connection.
        - Unplug the cable from the device, wait about 10 seconds, and plug it back in.
        - If it doesn't auto connect to the ethernet connection:
           - Network connections, disable ethernet, then enable ethernet

**The device is now connected to the region you have selected on your VPN.**
