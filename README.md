# Opencore-Lenovo-ThinkCentre-M80Q-Tiny
A repository of Opencore configuration made for the Lenovo ThinkCentre M80Q Tiny Desktop. 

## DISCLAIMER 
I will not be held responsible for any damage, permanent loss of data or any sorts of consequences that may arise by using my configuration files on your devices. Please use at your own risk.

## Current Release
- Opencore 0.7.9
- Monterey 12.3
- All latest kexts as of March 31, 2022

## Notebook Specifications

| Specification  | Model |  Remark  |
| ------------- | ------------- | ------------- |
| Chipset  | Intel Q470 | M2WKT4DA (7/12/2021)  |
| CPU  | Intel i5-10500T  |
| iGPU  | Intel UHD 630 | 
| Storage  | Samsung Evo 870 SATA 2.5 256GB  |
| RAM  | 8GB (1x8GB) 2666MHz DDR4 |
| Ethernet  | Intel I219-LM  |
| Wi-Fi  | Intel Wireless AC-8260  |
| Bluetooth  | Intel Bluetooth   |
| Audio  | Realtek ALC897Q (layout 11)   |


## What's working
- Mostly everything
- Wi-Fi & Bluetooth, Ethernet
- Display outputs (DP + HDMI)
- Headphone jack, microphone
- USB ports mapping
- Sleep/wake/shutdown

## What's not working
- N/A

## Not tested
- AppleID and iServices

## Quirks/issues
- N/A

## Bios Settings
Restore default settings and change the following:

- Devices > Video Setup > 
   -  Select Active Video > IGD
   -  Pre-Allocated Memory Size > 64 MB
- Advanced 
  - CPU Setup >
   - Intel(R) Hyper-Threading Technology > Enabled
   - Intel(R) Virtualization Technology > Enabled
   - VT-d Feature > Disable
   - TxT > Disable
  - Intel(R) Software Guard Extensions > Disable
- Security >
  - TCG Feature Setup > Disable
  - Secure Boot > Disable
  - Device Guard > Disable
- Startup
  - Fast Boot > Disable

## Credits
- All credits & rights goes to the maintainers, contributors and developers of the Opencore project and respective kernel extensions.
- Apple Inc.
