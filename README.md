# vpnc for the UP VPN

This will work on all/most Linux and OSX systems, and might work on BSDs as well (not tested yet).

1. Make sure your system has the vpnc binary available: `which vpnc`
2. If the binary is not available, install it from your Linux repo or use [homebrew](https://brew.sh/ "Homebrew") to install it (`brew install vpnc`). It should be installed by default on all Mac systems.
3. As root (sudo), copy the `vpnc` folder to your system's `/etc` directory
4. Run `sudo vpnc` to connect to the UP VPN. It will ask for your portal username and password. After that, the daemon will run in the background.
5. To disconnect from the VPN, run `sudo vpnc-disconnect`

# Todo:
- [ ] Test on FreeBSD
- [ ] Update info about whether it works on BSDs